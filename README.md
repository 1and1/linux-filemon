linux-filemon
=============

Filemonitor is an experimental Linux patch developed at [1&1 Internet AG](http://1und1.de). It provides dentry-based file event notifications for the entire virtual filesystem, useful for backup and antivirus systems.

WARNING! This patch has been designed as EXPERIMENTAL. Its usage is DANGEROUS, because some filesystems could get exhausted by the masses of ORPHAN INODES!

The current version of Filemonitor is 0.1. We provide the patch for the following stable Linux trees:
* 3.2 (3.2.28)
    * patch: [filemonitor-0.1-linux-3.2.28-201208212028.patch](https://github.com/downloads/1and1/linux-filemon/filemonitor-0.1-linux-3.2.28-201208212028.patch) - initial patch against the stable Linux 3.2 tree
    * commit: [5d55b7705f](https://github.com/1and1/linux-filemon/commit/5d55b7705f05d5e3dc38e3881a963d2cdc09f3b8) - Filemonitor commit to the Linux 3.2 branch
    * tarball: [linux-3.2.28-filemon-0.1.tar.bz2](https://github.com/downloads/1and1/linux-filemon/linux-3.2.28-filemon-0.1.tar.bz2) - Linux 3.2.28 patched with Filemonitor
* 3.4 (3.4.10)
    * patch: [filemonitor-0.1-linux-3.4.10-201209041827.patch](https://github.com/downloads/1and1/linux-filemon/filemonitor-0.1-linux-3.4.10-201209041827.patch) - initial patch against the long-term stable Linux 3.4 tree
    * commit: [3def14ebf5](https://github.com/1and1/linux-filemon/commit/3def14ebf5c1ac8ea7710fbfdad41dad07ae2ec6) - Filemonitor commit to the Linux 3.4 branch
    * tarball: [linux-3.4.10-filemon-0.1.tar.bz2](https://github.com/downloads/1and1/linux-filemon/linux-3.4.10-filemon-0.1.tar.bz2) - Linux 3.4.10 patched with Filemonitor

For more options please visit the [Downloads section](https://github.com/1and1/linux-filemon/downloads). For a minimal documentation, please visit the [wiki](https://github.com/1and1/linux-filemon/wiki).

Filemonitor is [Free Software](http://www.gnu.org/philosophy/free-sw.en.html) under GNU GPLv2+. Distributed with Linux, the kernel, it can be used under the terms of GNU GPLv2.
