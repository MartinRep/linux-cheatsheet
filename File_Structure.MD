# Basic Linux File System Structure

  - common executables available for everyone, ex. cp rm ls  
`/bin`  
  - kernel and boot configuration  
`/boot`  
  - files which point to both physical and pseudo devices  
`/dev`  
  - system and program configuration files  
`/etc`  
  - non-root user home directories  
`/home`  
  - library files used by the system, include .so files and others  
`/lib`
`/lib32`
`/lib64`  
  - saved files due to failure  
`/lost+found`  
  - auto-mounting place for certain external devices on some distros  
`/media`  
  - place to mount various file systems  
`/mnt`  
  - various software  
`/opt`  
  - virtual filesystem for resources, processes, and more  
`/proc`  
  - root user home directory  
`/root`  
  - similar to /bin, but for system administrators, ex. fdisk  
`/sbin`  
  - temporary file storage, wiped out after reboot  
`/tmp`  
  - user programs, library files, docs, etc., ex. obs  
`/usr`  
  - variable files for various purposes, ex. logs, tz data  
`/var`  
  - compressed linux kernel  
`/vmlinuz -> boot/vmlinuz-4.15.0-43-generic`  