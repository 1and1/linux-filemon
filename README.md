linux-filemon
=============

Filemonitor is an experimental Linux patch developed at [1&1 Internet AG](http://1und1.de). It provides dentry-based file event notifications for the entire virtual filesystem, useful for backup and antivirus systems.

WARNING! This patch has been designed as EXPERIMENTAL. Its usage is DANGEROUS, because some filesystems could get exhausted by the masses of ORPHAN INODES!

Filemonitor versions:
* 0.1
    * patch: [filemonitor-0.1-linux-3.2.28-201208212028.patch](https://github.com/downloads/1and1/linux-filemon/filemonitor-0.1-linux-3.2.28-201208212028.patch) - initial patch against the stable Linux 3.2 tree
    * commit: 5d55b7705f05d5e3dc38e3881a963d2cdc09f3b8 - Filemonitor commit to the Linux 3.2 branch
    * tarball: [linux-3.2.28-filemon-0.1.tar.bz2](https://github.com/downloads/1and1/linux-filemon/linux-3.2.28-filemon-0.1.tar.bz2) - Linux 3.2.28 patched with Filemonitor

For more options please visit the [Downloads section](https://github.com/1and1/linux-filemon/downloads).

Filemonitor is [Free Software](http://www.gnu.org/philosophy/free-sw.en.html) under GNU GPLv2+. Distributed with Linux, the kernel, it can be used under the terms of GNU GPLv2.
