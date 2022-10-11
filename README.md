# Linux

## Linux Filesystem

### *Use "man heir" to find more insights on linux files system*

This directory contains all the configuration file of your application.
if something goes wrong you should be looking in this directory.
```
ls /etc/ 
```
This directory contains binaries for use by all users and also contains executable files, Linux commands that are used in single user mode, and common commands that are used by all the users, like cat, cp, cd, ls, etc
```
ls /bin
```
This directory contains binaries to configure the operating system and executable files. It only contains system binaries which require root privilege to perform certain tasks and are helpful for system maintenance purpose. e.g. fsck, root, init, ifconfig, etc 
```
ls /sbin
```
This directory contains shared libraries which are often used by the ‘/bin’ and ‘/sbin’ directories. It also contains kernel module. These filenames are identable as ld* or lib*.so.*
```
ls /lib
```
This directory's main purpose is to store optional application software packages. In many cases this is software from outside the distribution repository. Add-on applications from individual vendors should be installed in ‘/opt’. In some systems ‘/opt’ is empty as they may not have any add-on application.

```
ls /opt
```
This directory in Linux based systems contains necessary files that are temporarily required by the system as well as other software and applications running on the machine.

For example, when you are writing a document, all the content inside that document is saved as a temporary file inside the /tmp directory. After you have saved it, it gets stored in your preferred location, and the temporary file gets removed once you exit the document.

```
ls /tmp
```
This directory contains contains the linux boot configuration files. This is one of the MOST important folder. Removing anything from this directory or a file getting corrupted will result in a OS crash after reboot. You system won't be able to boot without files in the /boot directory.
```
ls /boot
```
This directory contain files that represent devices that are attached to the local system. However, these are not regular files that a user can read and write to; these files are called devices files or special files.
*Device files are abstractions of standard devices that applications interact with via I/O system calls.*
```
ls /dev
```
The /media directory contains subdirectories where removable media devices inserted into the computer are mounted. For example, when you insert a CD into your Linux system, a directory will automatically be created inside the /media directory. You can access the contents of the CD inside this directory.
```
ls /media
```

This directory and its subdirectories are intended for use as the temporary mount points for mounting storage devices, such as CDROMs, floppy disks and USB (universal serial bus) key drives. /mnt is a standard subdirectory of the root directory on Linux
```
ls /mnt
```
This directory is for each processes running on our system. It also contains some configuration files
```
ls /proc
```
This directory contains variable data files. This includes spool directories and files, administrative and logging data, and transient and temporary files.
```
ls /var
```

### There are 7 filetypes in Linix?

- Normal files
- Directories
- References to files
- Character device files
- Block device files
- Symbolic links
- Local domain sockets/named pipes)


