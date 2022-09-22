> NOTE:  every thing in linux is a file.

File system: to manage all file in a systematic form is file system.

Types of file system:
1. ext3 (extended)
2. ext4
3. XFS
4. FAT  etc...

To check which file system you are using:
command :  lsblk -f .

### structure:

     1. /boot : having files used by root loader (ex: grub).
     2. /dev   : system devices files (ex: speake, keyboard etc).
     3. /etc    : having configration files.
     4. /usr/bin :  binaries
     5. /usr/sbin : system binaries of the root directory
     6. /opt : installation of optional add-on applications.
     7. /proc : running process
     8. /usr/lib : C program library files neede by commands and apps
     9. /tmp : having temporary files
     10. /home : directories of users.
     11. /root : home directory of root user
     12. /var system logs
     13. /run systm daemons that start very early (ex: systemd and udev) to store temporary runtime files like PID.
     14. . /mnt to mount external filesystem( ex: NFS).
     15. /media : for CDROM mounts. 


