## 🗂️ Linux Directory Structure (Rooted at /)
At the top of the Linux filesystem is the root directory: /

Everything in Linux starts from / — even drives, devices, and temporary files.

## 🔧 System and Boot Directories

/bin	Essential user binaries (e.g. ls, cp, mv) used in single-user mode.

/sbin	System binaries (e.g. fsck, reboot, iptables) used by root or services.

/boot	Files needed for booting Linux, like the kernel (vmlinuz) and GRUB

/lib, /lib64	Shared libraries needed by binaries in /bin and /sbin

## 👤 User and Configuration Directories

/etc	System-wide configuration files (e.g. /etc/passwd, /etc/ssh/sshd_config)

/home	Home directories for users (/home/john)

/root	Home directory for root user (NOT under /home)

## 📁 Variable and Runtime Data

/var	Variable data like logs (/var/log), mail, spools, and PID files

/tmp	Temporary files; deleted on reboot

/run	Runtime files like process ID files, sockets (tmpfs, volatile)

## 📦 Package and App Data

/usr	User-installed software, binaries, libraries (/usr/bin, /usr/lib)

/usr/local	Locally compiled software not managed by package manager

/opt	Optional 3rd-party software (e.g. /opt/google/, /opt/docker/)

## 🧪 Devices and Mounts

/dev	Device files (e.g. /dev/sda, /dev/null, /dev/tty)

/proc	Kernel and process info (virtual filesystem)

/sys	System and hardware info (also virtual filesystem)

/mnt	Temporary mount point for filesystems (manually mounted)

/media	Auto-mounted drives like USB or CD-ROM
