



A = 文件系统故障所在的虚拟机<br>
  
	     # fdisk -l /dev/sdc > /var/tmp/fdisk_before.log  
	     # dumpe2fs /dev/sdc1 > /var/tmp/dumpe2fs_before.log  
	     # tune2fs -l /dev/sdc1 > /var/tmp/tune2fs_before.log  
	     # e2fsck -n /dev/sdc1 > /var/tmp/e2fsck._beforelog  

		# fsck -yM /dev/sdc1
  
