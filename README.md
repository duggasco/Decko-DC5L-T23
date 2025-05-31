Shop link: [Amazon](https://www.amazon.com/dp/B09GK7RHSM)

Model: DC5L

PTZ: yes

CPU: T23N

Sensors: sc3332p

Wireless: [BL-M35343XU1 _(WS73 based)_](https://github.com/gtxaspec/ws73v100-wifi)


**bootcmd:**
```

bootargs=console=ttyS1,115200n8 mem=41M@0x0 rmem=23M@0x2900000 init=/linuxrc rootfstype=squashfs root=/dev/mtdblock2 rw mtdparts=jz_sfc:288k(boot),1792K(kernel),5888K(rootfs),1792K(kernel2),5888K(rootfs2),672K(etc),64K(factory),16M@0(all)

```


**binwalk output:**

```
DECIMAL       HEXADECIMAL     DESCRIPTION
--------------------------------------------------------------------------------
183832        0x2CE18         CRC32 polynomial table, little endian
188092        0x2DEBC         LZO compressed data
189912        0x2E5D8         Android bootimg, kernel size: 0 bytes, kernel addr: 0x70657250, ramdisk size: 543519329 bytes, ramdisk addr: 0x6E72656B, product name: "mem boot start"
294912        0x48000         uImage header, header size: 64 bytes, header CRC: 0x84ABC04A, created: 2024-09-10 13:30:39, image size: 1707650 bytes, Data Address: 0x80010000, Entry Point: 0x803AD2B0, data CRC: 0x2C163A69, OS: Linux, CPU: MIPS, image type: OS Kernel Image, compression type: lzma, image name: "Linux-3.10.14__isvp_pike_1.0__"
294976        0x48040         LZMA compressed data, properties: 0x5D, dictionary size: 33554432 bytes, uncompressed size: -1 bytes
2129920       0x208000        Squashfs filesystem, little endian, version 4.0, compression:xz, size: 5256856 bytes, 448 inodes, blocksize: 262144 bytes, created: 2024-09-27 09:20:17
8159232       0x7C8000        uImage header, header size: 64 bytes, header CRC: 0x84ABC04A, created: 2024-09-10 13:30:39, image size: 1707650 bytes, Data Address: 0x80010000, Entry Point: 0x803AD2B0, data CRC: 0x2C163A69, OS: Linux, CPU: MIPS, image type: OS Kernel Image, compression type: lzma, image name: "Linux-3.10.14__isvp_pike_1.0__"
8159296       0x7C8040        LZMA compressed data, properties: 0x5D, dictionary size: 33554432 bytes, uncompressed size: -1 bytes
9994240       0x988000        Squashfs filesystem, little endian, version 4.0, compression:xz, size: 5256856 bytes, 448 inodes, blocksize: 262144 bytes, created: 2024-09-27 09:20:17
16023552      0xF48000        JFFS2 filesystem, little endian
16351432      0xF980C8        Zlib compressed data, compressed
16352244      0xF983F4        Zlib compressed data, compressed
16353172      0xF98794        Zlib compressed data, compressed
16353636      0xF98964        Zlib compressed data, compressed
16353916      0xF98A7C        Zlib compressed data, compressed
16354728      0xF98DA8        Zlib compressed data, compressed
16355656      0xF99148        Zlib compressed data, compressed
16356120      0xF99318        Zlib compressed data, compressed
16356400      0xF99430        Zlib compressed data, compressed
16357312      0xF997C0        Zlib compressed data, compressed
16358240      0xF99B60        Zlib compressed data, compressed
16358704      0xF99D30        Zlib compressed data, compressed
16358984      0xF99E48        Zlib compressed data, compressed
16359412      0xF99FF4        JFFS2 filesystem, little endian
16359740      0xF9A13C        Zlib compressed data, compressed
16359884      0xF9A1CC        Zlib compressed data, compressed
16360000      0xF9A240        Zlib compressed data, compressed
16360116      0xF9A2B4        Zlib compressed data, compressed
16360232      0xF9A328        Zlib compressed data, compressed
16360348      0xF9A39C        Zlib compressed data, compressed
16360464      0xF9A410        Zlib compressed data, compressed
16360580      0xF9A484        Zlib compressed data, compressed
16360604      0xF9A49C        JFFS2 filesystem, little endian
16360960      0xF9A600        Zlib compressed data, compressed
16361132      0xF9A6AC        Zlib compressed data, compressed
16361248      0xF9A720        Zlib compressed data, compressed
16361364      0xF9A794        Zlib compressed data, compressed
16361480      0xF9A808        Zlib compressed data, compressed
16361596      0xF9A87C        Zlib compressed data, compressed
16361712      0xF9A8F0        Zlib compressed data, compressed
16361828      0xF9A964        Zlib compressed data, compressed
16361852      0xF9A97C        JFFS2 filesystem, little endian
16362160      0xF9AAB0        Zlib compressed data, compressed
16362356      0xF9AB74        Zlib compressed data, compressed
16362472      0xF9ABE8        Zlib compressed data, compressed
16362588      0xF9AC5C        Zlib compressed data, compressed
16362704      0xF9ACD0        Zlib compressed data, compressed
16362820      0xF9AD44        Zlib compressed data, compressed
16362936      0xF9ADB8        Zlib compressed data, compressed
16363052      0xF9AE2C        Zlib compressed data, compressed
16363076      0xF9AE44        JFFS2 filesystem, little endian
16363652      0xF9B084        Zlib compressed data, compressed
16363864      0xF9B158        Zlib compressed data, compressed
16363980      0xF9B1CC        Zlib compressed data, compressed
16364096      0xF9B240        Zlib compressed data, compressed
16364212      0xF9B2B4        Zlib compressed data, compressed
16364328      0xF9B328        Zlib compressed data, compressed
16364444      0xF9B39C        Zlib compressed data, compressed
16364560      0xF9B410        Zlib compressed data, compressed
16364584      0xF9B428        JFFS2 filesystem, little endian
16364756      0xF9B4D4        Zlib compressed data, compressed
16364996      0xF9B5C4        Zlib compressed data, compressed
16365112      0xF9B638        Zlib compressed data, compressed
16365228      0xF9B6AC        Zlib compressed data, compressed
16365344      0xF9B720        Zlib compressed data, compressed
16365460      0xF9B794        Zlib compressed data, compressed
16365576      0xF9B808        Zlib compressed data, compressed
16365692      0xF9B87C        Zlib compressed data, compressed
16365716      0xF9B894        JFFS2 filesystem, little endian
16365996      0xF9B9AC        Zlib compressed data, compressed
16366236      0xF9BA9C        Zlib compressed data, compressed
16366352      0xF9BB10        Zlib compressed data, compressed
16366468      0xF9BB84        Zlib compressed data, compressed
16366584      0xF9BBF8        Zlib compressed data, compressed
16366700      0xF9BC6C        Zlib compressed data, compressed
16366816      0xF9BCE0        Zlib compressed data, compressed
16366932      0xF9BD54        Zlib compressed data, compressed
16366956      0xF9BD6C        JFFS2 filesystem, little endian
16367500      0xF9BF8C        Zlib compressed data, compressed
16367760      0xF9C090        Zlib compressed data, compressed
16367876      0xF9C104        Zlib compressed data, compressed
16367992      0xF9C178        Zlib compressed data, compressed
16368108      0xF9C1EC        Zlib compressed data, compressed
16368224      0xF9C260        Zlib compressed data, compressed
16368340      0xF9C2D4        Zlib compressed data, compressed
16368456      0xF9C348        Zlib compressed data, compressed
16368480      0xF9C360        JFFS2 filesystem, little endian
16368652      0xF9C40C        Zlib compressed data, compressed
16368940      0xF9C52C        Zlib compressed data, compressed
16369056      0xF9C5A0        Zlib compressed data, compressed
16369172      0xF9C614        Zlib compressed data, compressed
16369288      0xF9C688        Zlib compressed data, compressed
16369404      0xF9C6FC        Zlib compressed data, compressed
16369520      0xF9C770        Zlib compressed data, compressed
16369636      0xF9C7E4        Zlib compressed data, compressed
16369660      0xF9C7FC        JFFS2 filesystem, little endian
16369832      0xF9C8A8        Zlib compressed data, compressed
16370132      0xF9C9D4        Zlib compressed data, compressed
16370248      0xF9CA48        Zlib compressed data, compressed
16370364      0xF9CABC        Zlib compressed data, compressed
16370480      0xF9CB30        Zlib compressed data, compressed
16370596      0xF9CBA4        Zlib compressed data, compressed
16370712      0xF9CC18        Zlib compressed data, compressed
16370828      0xF9CC8C        Zlib compressed data, compressed
16370852      0xF9CCA4        JFFS2 filesystem, little endian
16372608      0xF9D380        Zlib compressed data, compressed
16373536      0xF9D720        Zlib compressed data, compressed
16374000      0xF9D8F0        Zlib compressed data, compressed
16374280      0xF9DA08        Zlib compressed data, compressed
16374824      0xF9DC28        Zlib compressed data, compressed
16375752      0xF9DFC8        Zlib compressed data, compressed
16376216      0xF9E198        Zlib compressed data, compressed
16376496      0xF9E2B0        Zlib compressed data, compressed
16377040      0xF9E4D0        Zlib compressed data, compressed
16377968      0xF9E870        Zlib compressed data, compressed
16378432      0xF9EA40        Zlib compressed data, compressed
16378712      0xF9EB58        Zlib compressed data, compressed
16379140      0xF9ED04        JFFS2 filesystem, little endian
16380528      0xF9F270        JFFS2 filesystem, little endian
16380808      0xF9F388        JFFS2 filesystem, little endian
16652004      0xFE16E4        Zlib compressed data, compressed
16653764      0xFE1DC4        JFFS2 filesystem, little endian
16656792      0xFE2998        Zlib compressed data, compressed
16657156      0xFE2B04        JFFS2 filesystem, little endian
16658188      0xFE2F0C        Zlib compressed data, compressed
16659060      0xFE3274        Zlib compressed data, compressed
16659628      0xFE34AC        JFFS2 filesystem, little endian
16662064      0xFE3E30        Zlib compressed data, compressed
16662484      0xFE3FD4        JFFS2 filesystem, little endian
16674360      0xFE6E38        Zlib compressed data, compressed
16675288      0xFE71D8        Zlib compressed data, compressed
16675752      0xFE73A8        Zlib compressed data, compressed
16676032      0xFE74C0        Zlib compressed data, compressed
16677392      0xFE7A10        Zlib compressed data, compressed
16678320      0xFE7DB0        Zlib compressed data, compressed
16678784      0xFE7F80        Zlib compressed data, compressed
16678912      0xFE8000        JFFS2 filesystem, little endian

```

binwalk export tree:

```
.
├── bin
│   ├── [ -> busybox
│   ├── [[ -> busybox
│   ├── ash -> busybox
│   ├── awk -> busybox
│   ├── base64 -> busybox
│   ├── basename -> busybox
│   ├── busybox
│   ├── cal -> busybox
│   ├── cat -> busybox
│   ├── catv -> busybox
│   ├── chgrp -> busybox
│   ├── chmod -> busybox
│   ├── chown -> busybox
│   ├── clear -> busybox
│   ├── cmp -> busybox
│   ├── cp -> busybox
│   ├── cryptpw -> busybox
│   ├── cttyhack -> busybox
│   ├── date -> busybox
│   ├── dd -> busybox
│   ├── deallocvt -> busybox
│   ├── df -> busybox
│   ├── diff -> busybox
│   ├── dirname -> busybox
│   ├── dmesg -> busybox
│   ├── dnsdomainname -> busybox
│   ├── dos2unix -> busybox
│   ├── du -> busybox
│   ├── dumpleases -> busybox
│   ├── echo -> busybox
│   ├── ed -> busybox
│   ├── egrep -> busybox
│   ├── env -> busybox
│   ├── false -> busybox
│   ├── fdflush -> busybox
│   ├── fgrep -> busybox
│   ├── find -> busybox
│   ├── flock -> busybox
│   ├── fold -> busybox
│   ├── free -> busybox
│   ├── fsync -> busybox
│   ├── ftpget -> busybox
│   ├── ftpput -> busybox
│   ├── fuser -> busybox
│   ├── getopt -> busybox
│   ├── grep -> busybox
│   ├── groups -> busybox
│   ├── gzip -> busybox
│   ├── hd -> busybox
│   ├── hexdump -> busybox
│   ├── hostid -> busybox
│   ├── hostname -> busybox
│   ├── hush -> busybox
│   ├── id -> busybox
│   ├── iostat -> busybox
│   ├── ipcalc -> busybox
│   ├── ipcrm -> busybox
│   ├── ipcs -> busybox
│   ├── kill -> busybox
│   ├── killall -> busybox
│   ├── less -> busybox
│   ├── linux32 -> busybox
│   ├── linux64 -> busybox
│   ├── ln -> busybox
│   ├── logger -> busybox
│   ├── login -> busybox
│   ├── logname -> busybox
│   ├── ls -> busybox
│   ├── lsof -> busybox
│   ├── lsusb -> busybox
│   ├── md5sum -> busybox
│   ├── mesg -> busybox
│   ├── mkdir -> busybox
│   ├── mknod -> busybox
│   ├── mkpasswd -> busybox
│   ├── mktemp -> busybox
│   ├── mount -> busybox
│   ├── mountpoint -> busybox
│   ├── mpstat -> busybox
│   ├── mv -> busybox
│   ├── nc -> busybox
│   ├── netstat -> busybox
│   ├── nmeter -> busybox
│   ├── nslookup -> busybox
│   ├── passwd -> busybox
│   ├── pgrep -> busybox
│   ├── pidof -> busybox
│   ├── ping -> busybox
│   ├── ping6 -> busybox
│   ├── pkill -> busybox
│   ├── pmap -> busybox
│   ├── printenv -> busybox
│   ├── printf -> busybox
│   ├── ps -> busybox
│   ├── pscan -> busybox
│   ├── pstree -> busybox
│   ├── pwd -> busybox
│   ├── pwdx -> busybox
│   ├── readlink -> busybox
│   ├── realpath -> busybox
│   ├── renice -> busybox
│   ├── reset -> busybox
│   ├── resize -> busybox
│   ├── rev -> busybox
│   ├── rm -> busybox
│   ├── rmdir -> busybox
│   ├── sed -> busybox
│   ├── seq -> busybox
│   ├── setarch -> busybox
│   ├── sh -> busybox
│   ├── sleep -> busybox
│   ├── smemcap -> busybox
│   ├── sort -> busybox
│   ├── stat -> busybox
│   ├── sum -> busybox
│   ├── sync -> busybox
│   ├── tail -> busybox
│   ├── tar -> busybox
│   ├── tcpsvd -> busybox
│   ├── telnet -> busybox
│   ├── test -> busybox
│   ├── tftp -> busybox
│   ├── time -> busybox
│   ├── timeout -> busybox
│   ├── top -> busybox
│   ├── touch -> busybox
│   ├── tr -> busybox
│   ├── traceroute -> busybox
│   ├── traceroute6 -> busybox
│   ├── true -> busybox
│   ├── tty -> busybox
│   ├── ttysize -> busybox
│   ├── udpsvd -> busybox
│   ├── umount -> busybox
│   ├── uname -> busybox
│   ├── unix2dos -> busybox
│   ├── unzip -> busybox
│   ├── uptime -> busybox
│   ├── usleep -> busybox
│   ├── uudecode -> busybox
│   ├── uuencode -> busybox
│   ├── vi -> busybox
│   ├── vlock -> busybox
│   ├── volname -> busybox
│   ├── watch -> busybox
│   ├── wc -> busybox
│   ├── wget -> busybox
│   ├── whoami -> busybox
│   ├── whois -> busybox
│   ├── xargs -> busybox
│   └── yes -> busybox
├── dev
├── etc
├── etc_default
│   ├── autorun_enable
│   ├── etc_helper.sh
│   ├── fs-version
│   ├── group
│   ├── init.d
│   │   ├── S20modules
│   │   ├── S80network
│   │   ├── S90application
│   │   └── rcS
│   ├── inittab
│   ├── mdev
│   │   ├── auto_do_mount.sh
│   │   ├── auto_mount.sh
│   │   ├── safe_run.sh
│   │   └── u_auto_mount.sh
│   ├── mdev.conf
│   ├── motd
│   ├── mtab
│   ├── passwd
│   ├── profile
│   ├── rootfs_env.sh
│   ├── sdcard.sh
│   ├── shadow
│   ├── sysctl.conf
│   ├── syslog.conf
│   └── version.txt
├── lib
│   ├── ld-uClibc-0.9.33.2.so
│   ├── ld-uClibc.so.0 -> ld-uClibc-0.9.33.2.so
│   ├── libc.so.0 -> libuClibc-0.9.33.2.so
│   ├── libcrypt-0.9.33.2.so
│   ├── libcrypt.so.0 -> libcrypt-0.9.33.2.so
│   ├── libdl-0.9.33.2.so
│   ├── libdl.so.0 -> libdl-0.9.33.2.so
│   ├── libgcc_s.so
│   ├── libgcc_s.so.1
│   ├── libm-0.9.33.2.so
│   ├── libm.so.0 -> libm-0.9.33.2.so
│   ├── libnsl-0.9.33.2.so
│   ├── libnsl.so.0 -> libnsl-0.9.33.2.so
│   ├── libpthread-0.9.33.2.so
│   ├── libpthread.so.0 -> libpthread-0.9.33.2.so
│   ├── libresolv-0.9.33.2.so
│   ├── libresolv.so.0 -> libresolv-0.9.33.2.so
│   ├── librt-0.9.33.2.so
│   ├── librt.so.0 -> librt-0.9.33.2.so
│   ├── libstdc++.so -> libstdc++.so.6.0.21
│   ├── libstdc++.so.6 -> libstdc++.so.6.0.21
│   ├── libstdc++.so.6.0.21
│   ├── libthread_db-0.9.33.2.so
│   ├── libthread_db.so.1 -> libthread_db-0.9.33.2.so
│   ├── libuClibc-0.9.33.2.so
│   ├── libutil-0.9.33.2.so
│   ├── libutil.so.0 -> libutil-0.9.33.2.so
│   └── modules
│       └── 3.10.14__isvp_pike_1.0__
├── linuxrc
├── media
├── mnt
│   ├── data
│   ├── record
│   ├── sdcard
│   └── sdx
├── opt
├── proc
├── root
├── run
├── sbin
│   ├── acpid -> ../bin/busybox
│   ├── addgroup -> ../bin/busybox
│   ├── adduser -> ../bin/busybox
│   ├── arp -> ../bin/busybox
│   ├── arping -> ../bin/busybox
│   ├── blkid -> ../bin/busybox
│   ├── bootchartd -> ../bin/busybox
│   ├── brctl -> ../bin/busybox
│   ├── chpasswd -> ../bin/busybox
│   ├── chroot -> ../bin/busybox
│   ├── delgroup -> ../bin/busybox
│   ├── deluser -> ../bin/busybox
│   ├── depmod -> ../bin/busybox
│   ├── devmem -> ../bin/busybox
│   ├── dhcprelay -> ../bin/busybox
│   ├── dnsd -> ../bin/busybox
│   ├── ether-wake -> ../bin/busybox
│   ├── fakeidentd -> ../bin/busybox
│   ├── fbset -> ../bin/busybox
│   ├── fdformat -> ../bin/busybox
│   ├── fdisk -> ../bin/busybox
│   ├── findfs -> ../bin/busybox
│   ├── flash_eraseall -> ../bin/busybox
│   ├── flashcp -> ../bin/busybox
│   ├── freeramdisk -> ../bin/busybox
│   ├── getty -> ../bin/busybox
│   ├── halt -> ../bin/busybox
│   ├── httpd -> ../bin/busybox
│   ├── hwclock -> ../bin/busybox
│   ├── ifconfig -> ../bin/busybox
│   ├── ifdown -> ../bin/busybox
│   ├── ifenslave -> ../bin/busybox
│   ├── ifplugd -> ../bin/busybox
│   ├── ifup -> ../bin/busybox
│   ├── inetd -> ../bin/busybox
│   ├── init -> ../bin/busybox
│   ├── insmod -> ../bin/busybox
│   ├── ip -> ../bin/busybox
│   ├── ipaddr -> ../bin/busybox
│   ├── iplink -> ../bin/busybox
│   ├── iproute -> ../bin/busybox
│   ├── iprule -> ../bin/busybox
│   ├── iptunnel -> ../bin/busybox
│   ├── killall5 -> ../bin/busybox
│   ├── klogd -> ../bin/busybox
│   ├── logread -> ../bin/busybox
│   ├── losetup -> ../bin/busybox
│   ├── lsmod -> ../bin/busybox
│   ├── makedevs -> ../bin/busybox
│   ├── mdev -> ../bin/busybox
│   ├── mkdosfs -> ../bin/busybox
│   ├── mkfs.fat
│   ├── mkfs.vfat -> ../bin/busybox
│   ├── mkswap -> ../bin/busybox
│   ├── modinfo -> ../bin/busybox
│   ├── modprobe -> ../bin/busybox
│   ├── nameif -> ../bin/busybox
│   ├── nbd-client -> ../bin/busybox
│   ├── ntpd -> ../bin/busybox
│   ├── pivot_root -> ../bin/busybox
│   ├── poweroff -> ../bin/busybox
│   ├── rdate -> ../bin/busybox
│   ├── rdev -> ../bin/busybox
│   ├── readprofile -> ../bin/busybox
│   ├── reboot -> ../bin/busybox
│   ├── rmmod -> ../bin/busybox
│   ├── route -> ../bin/busybox
│   ├── rtcwake -> ../bin/busybox
│   ├── setconsole -> ../bin/busybox
│   ├── slattach -> ../bin/busybox
│   ├── sulogin -> ../bin/busybox
│   ├── swapoff -> ../bin/busybox
│   ├── swapon -> ../bin/busybox
│   ├── switch_root -> ../bin/busybox
│   ├── sysctl -> ../bin/busybox
│   ├── syslogd -> ../bin/busybox
│   ├── telnetd -> ../bin/busybox
│   ├── tftpd -> ../bin/busybox
│   ├── tunctl -> ../bin/busybox
│   ├── udhcpc -> ../bin/busybox
│   ├── udhcpd -> ../bin/busybox
│   ├── vconfig -> ../bin/busybox
│   ├── watchdog -> ../bin/busybox
│   └── zcip -> ../bin/busybox
├── sys
├── tmp
├── usr
│   ├── bin
│   │   ├── audio
│   │   │   ├── de
│   │   │   │   ├── call
│   │   │   │   ├── calling
│   │   │   │   ├── connect_pwderr
│   │   │   │   ├── connect_succ
│   │   │   │   ├── connect_timeout
│   │   │   │   ├── connect_wifi
│   │   │   │   ├── not_answer
│   │   │   │   └── reply
│   │   │   │       ├── 21001
│   │   │   │       ├── 21002
│   │   │   │       └── 21003
│   │   │   ├── di
│   │   │   ├── du
│   │   │   ├── es
│   │   │   │   ├── call
│   │   │   │   ├── calling
│   │   │   │   ├── connect_pwderr
│   │   │   │   ├── connect_succ
│   │   │   │   ├── connect_timeout
│   │   │   │   ├── connect_wifi
│   │   │   │   ├── not_answer
│   │   │   │   └── reply
│   │   │   │       ├── 21001
│   │   │   │       ├── 21002
│   │   │   │       └── 21003
│   │   │   ├── fr
│   │   │   │   ├── call
│   │   │   │   ├── calling
│   │   │   │   ├── connect_pwderr
│   │   │   │   ├── connect_succ
│   │   │   │   ├── connect_timeout
│   │   │   │   ├── connect_wifi
│   │   │   │   ├── not_answer
│   │   │   │   └── reply
│   │   │   │       ├── 21001
│   │   │   │       ├── 21002
│   │   │   │       └── 21003
│   │   │   ├── it
│   │   │   │   ├── call
│   │   │   │   ├── calling
│   │   │   │   ├── connect_pwderr
│   │   │   │   ├── connect_succ
│   │   │   │   ├── connect_timeout
│   │   │   │   ├── connect_wifi
│   │   │   │   ├── not_answer
│   │   │   │   └── reply
│   │   │   │       ├── 21001
│   │   │   │       ├── 21002
│   │   │   │       └── 21003
│   │   │   ├── jp
│   │   │   │   ├── call
│   │   │   │   ├── calling
│   │   │   │   ├── connect_pwderr
│   │   │   │   ├── connect_succ
│   │   │   │   ├── connect_timeout
│   │   │   │   ├── connect_wifi
│   │   │   │   ├── not_answer
│   │   │   │   └── reply
│   │   │   │       ├── 21001
│   │   │   │       ├── 21002
│   │   │   │       └── 21003
│   │   │   ├── reset
│   │   │   ├── sd_insert
│   │   │   ├── touch_key
│   │   │   ├── us
│   │   │   │   ├── call
│   │   │   │   ├── calling
│   │   │   │   ├── connect_pwderr
│   │   │   │   ├── connect_succ
│   │   │   │   ├── connect_timeout
│   │   │   │   ├── connect_wifi
│   │   │   │   ├── not_answer
│   │   │   │   └── reply
│   │   │   │       ├── 21001
│   │   │   │       ├── 21002
│   │   │   │       └── 21003
│   │   │   └── wuwa
│   │   ├── ble_app
│   │   ├── cuftpd
│   │   ├── fm.aosulife.com.crt
│   │   ├── format_sd.sh
│   │   ├── impdbg
│   │   ├── ipc
│   │   ├── iwconfig
│   │   ├── iwlist
│   │   ├── iwpriv
│   │   ├── logcat
│   │   ├── nvram
│   │   ├── remount_sd.sh
│   │   ├── restart_wifi.sh
│   │   ├── sd_check
│   │   ├── sdcard_detect.sh
│   │   ├── watchdog.sh
│   │   ├── webrtc_profile.ini
│   │   ├── wpa_supplicant
│   │   └── ws73
│   │       ├── btc_cali.bin
│   │       ├── wifi_cali.bin
│   │       ├── wow.bin
│   │       └── ws73.bin
│   ├── etc
│   │   ├── loadmod.sh
│   │   ├── udhcpc.script
│   │   ├── wpa_supplicant.conf
│   │   └── ws73_cfg.ini
│   ├── lib
│   │   ├── libaudioProcess.so
│   │   ├── libiw.so.29
│   │   └── modules
│   │       ├── audio.ko
│   │       ├── ble_soc.ko
│   │       ├── exfat.ko
│   │       ├── insmod.sh
│   │       ├── motor_driver.ko
│   │       ├── plat_soc.ko
│   │       ├── sensor_sc3332p_t23.ko
│   │       ├── sinfo.ko
│   │       ├── tx-isp-t23.ko
│   │       └── wifi_soc.ko
│   ├── sensor
│   │   └── sc3332p-t23.bin
│   └── share
│       └── udhcpc
│           └── default.script
└── var
    ├── cache -> ../tmp
    ├── lib
    │   └── misc -> ../../tmp
    ├── lock -> ../tmp
    ├── log -> ../tmp
    ├── run -> ../run
    ├── spool -> ../tmp
    ├── tmp -> ../tmp
    └── www

```

**UART standard Boot Output**

```


U-Boot SPL 2013.07 (Aug 25 2024 - 18:37:48)
Board info: T23N

apll_freq = 1188000000
mpll_freq = 1200000000
sdram init start
DDR clk rate 600000000
DDR_PAR of eFuse: 00000000 00000000
sdram init finished
Enter spl_sfc_nor_load_image!
pull down gpio for WTLED!
pull down gpio for IRLED!
pull up gpio for GREEN LED force !
image entry point: 0x80100000


U-Boot 2013.07 (Aug 25 2024 - 18:37:48)

Board: ISVP (Ingenic XBurst T23 SoC)
DRAM:  64 MiB
Top of RAM usable for U-Boot at: 84000000
Reserving 415k for U-Boot at: 83f98000
Reserving 32800k for malloc() at: 81f90000
Reserving 32 Bytes for Board Info at: 81f8ffe0
Reserving 124 Bytes for Global Data at: 81f8ff64
Reserving 128k for boot params() at: 81f6ff64
Stack Pointer at: 81f6ff48
Now running in RAM - U-Boot at: 83f98000
MMC:   msc: 0
the manufacturer 20
SF: Detected XM25QH128C

In:    serial
Out:   serial
Err:   serial
RESET_BUTTON is not pressed!
glazero checking the system...
getenv system: <NULL>
curr system is: 0
Hit any key to stop autoboot:  0
the manufacturer 20
SF: Detected XM25QH128C

--->probe spend 4 ms
SF: 1835008 bytes @ 0x48000 Read: OK
--->read spend 591 ms
## Booting kernel from Legacy Image at 80600000 ...
   Image Name:   Linux-3.10.14__isvp_pike_1.0__
   Image Type:   MIPS Linux Kernel Image (lzma compressed)
   Data Size:    1707650 Bytes = 1.6 MiB
   Load Address: 80010000
   Entry Point:  803ad2b0
   Verifying Checksum ... OK
   Uncompressing Kernel Image ... OK

Starting kernel ...

[    0.000000] Initializing cgroup subsys cpu
[    0.000000] Initializing cgroup subsys cpuacct
[    0.000000] Linux version 3.10.14__isvp_pike_1.0__ (qiaoba@qiaoba-v) (gcc version 5.4.0 (Ingenic Linux-Release3.3.0-Default(xburst1(fp32)+uclibc0.9.33.2) Smaller libc 2022.11-07) ) #1 PREEMPT Tue Sep 10 21:30:20 CST 2024
[    0.000000] bootconsole [early0] enabled
[    0.000000] CPU0 RESET ERROR PC:F247220C
[    0.000000] CPU0 revision is: 00d00100 (Ingenic Xburst)
[    0.000000] FPU revision is: 00b70000
[    0.000000] cgu_macphy clk should be opened!
[    0.000000] cgu_vpu clk should be opened!
[    0.000000] CCLK:1188MHz L2CLK:594Mhz H0CLK:200MHz H2CLK:200Mhz PCLK:100Mhz
[    0.000000] Determined physical RAM map:
[    0.000000]  memory: 004c4000 @ 00010000 (usable)
[    0.000000]  memory: 0003c000 @ 004d4000 (usable after init)
[    0.000000] User-defined physical RAM map:
[    0.000000]  memory: 02900000 @ 00000000 (usable)
[    0.000000] Zone ranges:
[    0.000000]   Normal   [mem 0x00000000-0x028fffff]
[    0.000000] Movable zone start for each node
[    0.000000] Early memory node ranges
[    0.000000]   node   0: [mem 0x00000000-0x028fffff]
[    0.000000] Primary instruction cache 16kB, 8-way, VIPT, linesize 32 bytes.
[    0.000000] Primary data cache 16kB, 8-way, VIPT, no aliases, linesize 32 bytes
[    0.000000] pls check processor_id[0x00d00100],sc_jz not support!
[    0.000000] MIPS secondary cache 64kB, 8-way, linesize 32 bytes.
[    0.000000] Built 1 zonelists in Zone order, mobility grouping off.  Total pages: 10414
[    0.000000] Kernel command line: console=ttyS1,115200n8 mem=41M@0x0 rmem=23M@0x2900000 init=/linuxrc rootfstype=squashfs root=/dev/mtdblock2 rw mtdparts=jz_sfc:288k(boot),1792K(kernel),5888K(rootfs),1792K(kernel2),5888K(rootfs2),672K(etc),64K(factory),16M@0(all)
[    0.000000] PID hash table entries: 256 (order: -2, 1024 bytes)
[    0.000000] Dentry cache hash table entries: 8192 (order: 3, 32768 bytes)
[    0.000000] Inode-cache hash table entries: 4096 (order: 2, 16384 bytes)
[    0.000000] Memory: 35800k/41984k available (3733k kernel code, 6184k reserved, 1143k data, 240k init, 0k highmem)
[    0.000000] SLUB: HWalign=32, Order=0-3, MinObjects=0, CPUs=1, Nodes=1
[    0.000000] Preemptible hierarchical RCU implementation.
[    0.000000] NR_IRQS:347
[    0.000000] clockevents_config_and_register success.
[    0.000020] Calibrating delay loop... 1185.38 BogoMIPS (lpj=5926912)
[    0.087811] pid_max: default: 32768 minimum: 301
[    0.092707] Mount-cache hash table entries: 512
[    0.097742] Initializing cgroup subsys debug
[    0.102000] Initializing cgroup subsys freezer
[    0.108796] regulator-dummy: no parameters
[    0.113036] NET: Registered protocol family 16
[    0.129411] bio: create slab <bio-0> at 0
[    0.135551] jz-dma jz-dma: JZ SoC DMA initialized
[    0.140538] usbcore: registered new interface driver usbfs
[    0.146157] usbcore: registered new interface driver hub
[    0.151590] usbcore: registered new device driver usb
[    0.156853]  (null): set:249  hold:250 dev=100000000 h=500 l=500
[    0.162971]  (null): set:61  hold:62 dev=100000000 h=125 l=125
[    0.169516] Bluetooth: Core ver 2.16
[    0.173117] NET: Registered protocol family 31
[    0.177601] Bluetooth: HCI device and connection manager initialized
[    0.184026] Bluetooth: HCI socket layer initialized
[    0.188970] Bluetooth: L2CAP socket layer initialized
[    0.194098] Bluetooth: SCO socket layer initialized
[    0.200236] Switching to clocksource jz_clocksource
[    0.205187] cfg80211: Calling CRDA to update world regulatory domain
[    0.212206] NET: Registered protocol family 2
[    0.217120] TCP established hash table entries: 512 (order: 0, 4096 bytes)
[    0.224076] TCP bind hash table entries: 512 (order: -1, 2048 bytes)
[    0.230474] TCP: Hash tables configured (established 512 bind 512)
[    0.236804] TCP: reno registered
[    0.240010] UDP hash table entries: 256 (order: 0, 4096 bytes)
[    0.245968] UDP-Lite hash table entries: 256 (order: 0, 4096 bytes)
[    0.252530] NET: Registered protocol family 1
[    0.257186] RPC: Registered named UNIX socket transport module.
[    0.263183] RPC: Registered udp transport module.
[    0.267883] RPC: Registered tcp transport module.
[    0.272668] RPC: Registered tcp NFSv4.1 backchannel transport module.
[    0.279506] freq_udelay_jiffys[0].max_num = 10
[    0.283977] cpufreq  udelay  loops_per_jiffy
[    0.288348] 12000     59867   59867
[    0.291627] 24000     119735  119735
[    0.295058] 60000     299338  299338
[    0.298501] 120000    598677  598677
[    0.302079] 200000    997796  997796
[    0.305565] 300000    1496694         1496694
[    0.309273] 600000    2993389         2993389
[    0.313001] 792000    3951274         3951274
[    0.316690] 1008000   5028895         5028895
[    0.320486] 1200000   5986779         5986779
[    0.328826] squashfs: version 4.0 (2009/01/31) Phillip Lougher
[    0.335639] jffs2: version 2.2. © 2001-2006 Red Hat, Inc.
[    0.341489] msgmni has been set to 69
[    0.347075] io scheduler noop registered
[    0.351002] io scheduler cfq registered (default)
[    0.356043] wait stable.[288][cgu_vpu]
[    0.359767] cgu_vpu can not set to 450000000, will change!!!
[    0.366979] jz-uart.1: ttyS1 at MMIO 0x10031000 (irq = 58) is a uart1
[    0.374768] console [ttyS1] enabled, bootconsole disabled
[    0.374768] console [ttyS1] enabled, bootconsole disabled
[    0.389790] brd: module loaded
[    0.395144] loop: module loaded
[    0.399010] zram: Created 2 device(s) ...
[    0.403345] logger: created 256K log 'log_main'
[    0.408412] jz TCU driver register completed
[    0.413336] the id code = 204018, the flash name is XM25QH128C
[    0.419386] jz-sfc jz-sfc: sfc use DMA mode
[    0.423768] jz-sfc jz-sfc: nor flash now use standard mode!
[    0.429537] JZ SFC Controller for SFC channel 0 driver register
[    0.435698] 8 cmdlinepart partitions found on MTD device jz_sfc
[    0.441844] Creating 8 MTD partitions on "jz_sfc":
[    0.446807] 0x000000000000-0x000000048000 : "boot"
[    0.452318] 0x000000048000-0x000000208000 : "kernel"
[    0.458005] 0x000000208000-0x0000007c8000 : "rootfs"
[    0.463720] 0x0000007c8000-0x000000988000 : "kernel2"
[    0.469457] 0x000000988000-0x000000f48000 : "rootfs2"
[    0.475256] 0x000000f48000-0x000000ff0000 : "etc"
[    0.480644] 0x000000ff0000-0x000001000000 : "factory"
[    0.486447] 0x000000000000-0x000001000000 : "all"
[    0.491888] SPI NOR MTD LOAD OK
[    0.495198] tun: Universal TUN/TAP device driver, 1.6
[    0.500424] tun: (C) 1999-2004 Max Krasnyansky <maxk@qualcomm.com>
[    0.506996] usbcore: registered new interface driver zd1201
[    0.512924] DWC IN OTG MODE
[    0.516450] dwc2 dwc2: Keep PHY ON
[    0.519974] dwc2 dwc2: Using Buffer DMA mode
[    0.524438] dwc2 dwc2: Core Release: 3.00a
[    0.528714] dwc2 dwc2: DesignWare USB2.0 High-Speed Host Controller
[    0.535208] dwc2 dwc2: new USB bus registered, assigned bus number 1
[    0.542558] hub 1-0:1.0: USB hub found
[    0.546458] hub 1-0:1.0: 1 port detected
[    0.550678] dwc2 dwc2: DWC2 Host Initialized
[    0.555545] usbcore: registered new interface driver btusb
[    0.561307] cgu_msc0 can not set to 24000000, will change!!!
[    0.567236] jzmmc_v1.2 jzmmc_v1.2.0: vmmc regulator missing
[    0.573419] jzmmc_v1.2 jzmmc_v1.2.0: register success!
[    0.579003] TCP: cubic registered
[    0.582539] NET: Registered protocol family 17
[    0.587524] soc_vpu probe success,version:1.0.0-03203fd46d
[    0.593533] input: gpio-keys as /devices/platform/gpio-keys/input/input0
[    0.600854] drivers/rtc/hctosys.c: unable to open rtc device (rtc0)
[    0.612203] VFS: Mounted root (squashfs filesystem) readonly on device 31:2.
[    0.619873] Freeing unused kernel memory: 240K (804d4000 - 80510000)
[    0.628712] dwc2 dwc2: ID PIN CHANGED!
/
/
[RCS]: /etc_default/init.d/S20modules
[    1.432244] zram0: detected capacity change from 0 to 8388608
Setting up swapspace version 1, size = 8384512 bytes
UUID=e9372fb5-8a10-40a4-aec9-8[    1.444102] Adding 8188k swap on /dev/zram0.  Priority:-1 extents:1 across:8188k SS
3366062802a
[    1.901661] usb 1-1: new full-speed USB device number 2 using dwc2
insmod ko of WS73!
[    2.622963] plat_soc:W]ini_file_name@/etc/ws73_cfg.ini
[    2.634957] plat_soc:EMERG]0:emerg log.
[    2.639021] plat_soc:ALERT]1:alert log.
[    2.643145] plat_soc:CRIT]2:crit log.
[    2.647024] plat_soc:E]3:err log.
[    2.650538] plat_soc:W]4:warning log.
[    2.654465] plat_soc:E]custom ini[plat kern log level]: 7.
[    2.662605] plat_soc:E]board_power_gpio_init::request power_gpio fail.
[    2.721854] plat_soc:E]board_power_gpio_init::succ, power_gpio_idx=[6]!
[    2.729821] plat_soc:E]board_wakeup_gpio_init::get wkup_gpio_idx invalid, value=[-1].
[    2.738474] plat_soc:E]diag uart file open failed
[    2.745642] plat_soc:E]zdiag_adapt_init::zdiag_channel_init err[-1].
[    2.752462] [USB][I]OFF --> INIT
[    2.752462] [usb_set_bus_state:87]
[    2.759451] [USB][I]boot usb[oal_usb_probe:1420]
[    2.764409] [USB][I]bulk_in_ep:0x81[oal_usb_boot_bulk_in_probe:1320]
[    2.771088] [USB][I]dev->bulk_out_ep:0x1[oal_usb_boot_bulk_out_probe:1351]
[    2.778352] [USB][I]INIT --> BOOT
[    2.778352] [usb_set_bus_state:87]
[    2.785430] [USB][I]usb boot probe success[oal_usb_boot_init_config:1394]
[    2.792952] usbcore: registered new interface driver wireless_usb
[    2.800306] plat_soc:E]hcc diag log service ini ok
[    2.807624] plat_soc:W]plat_misc_init!
[    2.811712] plat_soc:W]plat_init_etc::succ!
[    2.811712]
[    3.148470] insmod wifi ko beginning!
[    3.154714] [osal_kthread_set_priority_ws73:50]:task is invalid!
[    3.161028] [osal_kthread_set_priority_ws73:50]:task is invalid!
[    3.167340] [FRW] frw_timer_init enter
[    3.171321] frw_start_hcc_service type:6, ret=0
[    3.176154] frw_start_hcc_service type:4, ret=0
[    3.180933] [FRW] frw_main_init_etc end
[    3.202756] plat_soc:E]check if var and value is NULL or blank
[    3.208625] plat_soc:E]check if var and value is NULL or blankhwifi_custom_host_read_cfg_init finish!
[    3.250805] hwifi_cfg_host_global_init_param: rx_stbc[1] ret[0]
[    3.257056] hwifi_cfg_tcp_ack_param_init: tcp_ack_filter_enable[0] ret[0]
[    3.264188] hwifi_cfg_tcp_ack_param_init: tcp_ack_max_num_start_process[2] ret[0]
[    3.272069] hwifi_cfg_host_global_init_param: user num[8] ret[0]
[    3.278379] hwifi_cfg_scan_para_cfg_init probe send times, ret 0 priv_value 2
[    3.285876] get scan time, ret 0 priv_value 30
[    3.290564] get scan count, ret 0 priv_value 2
[    3.295267] hwifi_cfg_scan_probe_ie_cfg_init ret 0 priv_value 1
[    3.301484] hwifi_cfg_scan_probe_del_wps_ie_cfg_init ret 0 priv_value 1
[    3.308433] g_scan_probe_req_del_wps_ie = 1
[    3.312864] hwifi_cfg_random_mac_addr_scan_init ret 0 priv_value 1
[    3.319351] hwifi_cfg_random_mac_addr_scan_oui_init ret 65535 priv_value 0
[    3.326570] hwifi_cfg_pcap_file_len_max_cfg_init ret 0 priv_value 12
[    3.333249] hwifi_cfg_host_global_init_param: 11ax protocol enable[0] ret[0]
[    3.340635] hwifi_cfg_host_global_init_param: smooth_phase_en[1] ret[0]
[    3.347583] hwifi_cfg_host_global_init_param: over_ds_en[1] ret[0]
[    3.354266] {wal_set_wlan_name_config::g_wlan_name[0]=wlan0}
[    3.360371] {wal_set_wlan_name_config::g_wlan_name[1]=wlan1}
[    3.366526] {wal_set_wlan_name_config::g_wlan_name[2]=p2p0}
[    3.375916] hmac_register_pm_callback_etc:wlan_pm_get_wifi_srv_handler_etc is null
[    3.418047] plat_soc:E]pm_svc_open::first svc open, pm_svc_power_on!
[    3.497621] plat_soc:E]firmware_download_etc begin
[    3.740980] usb 1-1: USB disconnect, device number 2
[    3.746267] [USB][I]usb disconnect
[    3.746267] [oal_usb_disconnect:1582]
[    3.753789] [USB][I]BOOT --> DISCONNECT
[    3.753789] [usb_set_bus_state:87]
[    4.111660] usb 1-1: new high-speed USB device number 3 using dwc2
[    4.332143] [USB][I]kernel usb[oal_usb_probe:1415]
[    4.337204] [USB][I]7 5 81 2 200 0[oal_usb_system_init_bulk_ep:946]
[    4.346149] [USB][I]EP bulk_in:129, bulk_out:1, int_in:131[oal_usb_system_ep_init:1043]
[    4.354607] [USB][I]rw reg ep_in:[130], ep_out:[2][oal_usb_init_rw_reg_ep:924]
[    4.362417] [USB][I]start[usb_transfer_rx_data_handle:793]
[    4.368424] [USB][I]DISCONNECT --> WORK
[    4.368424] [usb_set_bus_state:87]
[    4.376098] plat_soc:E]plat handle hcc msg dev_bsp_ready_cb.
[    4.382076] plat_soc:E]===BSP READY==
[    4.385940] [USB][I]usb_reload succ[hcc_usb_reload:1664]
[    4.391535] plat_soc:E]firmware_download_etc::succ!
[    4.396729] [USB][I]oal_usb_probe success![oal_usb_system_init_config:1095]
[    4.404358] plat_soc:W]download firmware, count [1], current time [906733]us, max time [906733]us
[    4.420696] plat_soc:E]ini get mac_addr failed
[    4.432104] plat_soc:W]power on, count [1], current time [1004993]us, max time [1004993]us
[    4.440664] plat_soc:W]pm_svc_open::first svc open, pm_svc_power_on succ!
[    4.447810] plat_soc:E]pm_svc_open::wlan open.
[    4.452514] plat_soc:E]pm_svc_open::SUCC!
[    4.456754] plat_soc:E]wlan_power_open_cmd[    4.461732] plat_soc:E]===wlan READY==
hwifi_custom_adapt_mac_device_priv_ini_param::ldpc[1].
[    4.487047] hwifi_custom_adapt_mac_device_priv_ini_param::front_switch[0].
[    4.494296] hwifi_custom_adapt_device_priv_ini_cali_mask_param::read cali_mask[8110]ret[0]
[    4.502962] hwifi_custom_adapt_mac_device_priv_ini_param::g_uc_wlan_open_cnt[1]priv_cali_data_up_down[0x14]
[    4.513151] hwifi_custom_adapt_mac_device_priv_ini_param::g_uc_custom_cali_done_etc[0]auto_cali_mask[0x0]
[    4.523159] hwifi_custom_adapt_device_priv_ini_param::data_len[46]
[    4.529644] ***hwifi_hcc_custom_ini_data_buf:46 ***********
[    4.535646] ***hwifi_hcc_custom_ini_data_buf:22 ***********
[    4.548891] ===hal_initialize_phy===269===
[    4.619286] ====hal_device_state_init_event=====623===21=
[    4.629333] hwifi_get_country_code_etc suc: code:CN
[    4.634778] hwifi_get_region 99: region not found
[    4.639796] hwifi_get_region find CN in region_table_default
[    4.713834] plat_soc:E]===wlan READY==
[    4.718419] vap_id[0] {hmac_config_set_cus_dts_cali::cali time[27]ms ret[0]}save cali data len:864 ret:0.
[    4.728545] plat_soc:E]78:22:88:99:96:91
[    4.732820] plat_soc:E]wlan_close_etc, exit_later_func
[    4.738589] plat_soc:E]pm_svc_close::not rmmod svc [0], return.
[    4.744852] wifi_host_init_finish![wifi_cali2 cost 1559 ms].
[    4.750716] insmod wifi ko finished!
[    4.755874] host_module_init_etc:: host_main_init finish!
[    4.761556] WiFi Init OK.
[    4.764294] wifi_host_init_finish![wifi_init cost 1578 ms].
[    4.884127] plat_soc:E]***hbsle_hcc_custom_ini_data_buf:140 ***********
[    4.891051] [HCC] enter:hcc_adapt_bsle_msg_free
[    4.895933] [HCC] get bsle custom para data
[    4.900383] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    4.907327] [HCC] get device status:2,result:1,time:0
[    4.912703] plat_soc:W]bsle_open_close_cmd, service[1], type[1].
[    4.919135] plat_soc:E]pm_svc_open::SUCC!
[    4.923552] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    4.930526] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    4.937574] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    4.944530] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    4.951580] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    4.958534] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    4.965442] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    4.972317] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    4.979767] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    4.986663] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    4.993533] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    5.000381] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    5.007248] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    5.014111] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    5.020961] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    5.027823] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    5.034685] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    5.041534] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    5.048401] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    5.055265] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:2
[    5.062127] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:2,device_msg:1
[    5.068982] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:4,device_msg:0
[    5.075843] [HCC] Get bsle device action msg, type=[0]
[    5.081249] [HCC] ble_enable_reply_cb is NULL, return!
[    5.086691] [HCC] get device status:1,result:1,time:0
[    5.092400] [BT_DEV_INFO] register platform bt device ret:0
[    5.103299] [BT_DEV_INFO] bt_probe:354 ret:0
[    5.108077] [BT_DEV_INFO] register platform bt driver ret:0
net.ipv4.udp_mem = 858 1145 1716
net.core.rmem_default = 716800
net.core.rmem_max = 716800
net.ipv4.tcp_rmem = 4096 87380 444384
[    5.133553] exFAT: file-system version 2.2.0-3arter97
/
[    5.162507] name : i2c0 nr : 0
[    5.165679] cgu_cim can not set to 27000000, will change!!!
[    5.252147]  sensor_read: addr=0x3107 value = 0xcc
[    5.257632]  sensor_read: addr=0x3108 value = 0x44
[    5.262630] cgu_cim can not set to 27000000, will change!!!
[    5.352147]  sensor_read: addr=0x3107 value = 0xcc
[    5.357629]  sensor_read: addr=0x3108 value = 0x44
[    5.363129]  sensor_read: addr=0x801b value = 0xf
[    5.367996] break for the next!
[    5.371347] cgu_cim can not set to 27000000, will change!!!
[    5.462158]  sensor_read: addr=0x3107 value = 0xcc
[    5.467640]  sensor_read: addr=0x3108 value = 0x44
[    5.473140]  sensor_read: addr=0x801b value = 0xf
[    5.478008] probe sensor is sc3332p!
[    5.481730] info: success sensor find : sc3332p
[    5.486421] name : i2c2 nr : 2
sensor :sc3332p
--------------------
isp_clk=200000000
[    5.720598] cgu_isp can not set to 153000000, will change!!!
[    5.726840] cgu_vpu can not set to 416000000, will change!!!
[    5.761834] @@@@ tx-isp-probe ok(version H20240204a), compiler date=Feb  4 2024 @@@@@
[    5.797139] pipe_request_dma: paddr = 0x1f00000
[    5.804292] dma dma0chan24: Channel 24 have been requested.(phy id 7,type 0x06 desc a27c2000)
[    5.813537] pipe_request_dma: paddr = 0x1f40000
[    5.818270] dma dma0chan25: Channel 25 have been requested.(phy id 6,type 0x06 desc a08d6000)
[    5.827498] pipe_request_dma: paddr = 0x1e80000
[    5.832322] dma dma0chan26: Channel 26 have been requested.(phy id 5,type 0x04 desc a08b0000)
[    5.861634] @@@@@ inner codec power up@@@@@@
[    6.271690] @@@@ audio driver ok(version H20230614a) @@@@@
[    6.305474] i2cmotor_init success!
[RCS]: /etc_default/init.d/S80network
gz_custom_get_userinfo_size:[65536]
read mac len:32, data:60:d5:61:1f:4a:39
wifimac: 60:d5:61:1f:4a:39
config wifi mac! wifimac: 60:d5:61:1f:4a:39
[    6.601892] wal_netdev_set_mac_addr
[    6.608327] wal_netdev_open_etc,dev_name is:wlan0
[    6.613280] plat_soc:E]pm_svc_open::not insmod service[0], return already opened.
[    6.621118] plat_soc:E]wlan_power_open_cmd[    6.626316] plat_soc:E]===wlan READY==
hwifi_custom_adapt_mac_device_priv_ini_param::ldpc[1].
[    6.651763] hwifi_custom_adapt_mac_device_priv_ini_param::front_switch[0].
[    6.658975] hwifi_custom_adapt_device_priv_ini_cali_mask_param::read cali_mask[8110]ret[0]
[    6.667655] hwifi_custom_adapt_mac_device_priv_ini_param::g_uc_wlan_open_cnt[2]priv_cali_data_up_down[0x10]
[    6.677849] hwifi_custom_adapt_mac_device_priv_ini_param::g_uc_custom_cali_done_etc[1]auto_cali_mask[0x0]
[    6.687858] hwifi_custom_adapt_device_priv_ini_param::data_len[46]
[    6.694357] ***hwifi_hcc_custom_ini_data_buf:46 ***********
[    6.700349] ***hwifi_hcc_custom_ini_data_buf:22 ***********
[    6.706801] func[frw_msg_exec_callback] line[324] msg_id[47] callback unregistered
[    6.721190] ===hal_initialize_phy===269===
[    6.790229] ====hal_device_state_init_event=====623===21=
[    6.800255] hwifi_get_country_code_etc already set country:CN
[    6.806431] hwifi_get_region find CN in region_table_default
[    6.812478] hwifi_get_region find CN in region_table_default
[    6.819851] vap_id[0] {hmac_config_set_cus_dts_cali::cali time[1]ms ret[0]}wifi_host_init_finish![wifi_cali2 cost 3592 ms].
[    6.831496] plat_soc:E]===wlan READY==
[    6.840208] hmac_fsm_change_state_etc state 5, vap_id 1
[RCS]: /etc_default/init.d/S90application
gz_custom_get_userinfo_size:[65536]
read uid len:96, data:DK:xtsycpfo1a1fzkqu:lzgd46ebc2a39a329cc2:UqwutU7ekcisEv8cYyrYuqItA3PzhRKy:C5L2DA110030399
mmc det ok during system startup !
Auto login as root ...
(none) login: 01-01 08:00:07.680 run system cmd |mkdir -p /tmp/mmcblk0p1/data| return 0
[01-01 08:00:07.680 AV]: gz_watchdog_open enter!
[01-01 08:00:07.680 AV]: gz_watchdog_open success!
[01-01 08:00:07.684 AV]: gz_watchdog_feed success!
[01-01 08:00:07.685 AV]: gz_hal_led_init success! igpionum = 58
[55]gz_dev_button_init!
[01-01 08:00:07.687 AV]: gz_video_input_init ++++++++
[01-01 08:00:07.687 AV]: gz_system_init start
[205] print times frome system start ! time = 7687
[01-01 08:00:07.687 AV]: p = sensor :sc3332p
[01-01 08:00:07.688 AV]: sensor_name = sc3332p
[01-01 08:00:07.688 AV]: sizeof(Def_Sensor_Info.i2c.type) === 20
[36] type:1, code:28, value:1
[45] button pops up!
[    7.892157] -----sc3332p_detect: 734 ret = 0, v = 0xcc
[    7.898037] -----sc3332p_detect: 742 ret = 0, v = 0x44
[    7.903382] sc3332p chip found @ 0x30 (i2c0)
[    7.907823] sensor driver version H20240522a
[    8.101643] Ivdc init! direct_mode is 1
[    8.137649] sc3332p stream on
[01-01 08:00:08.177 AV]: gz_system_init success!
[01-01 08:00:08.177 AV]: gz_framesource_init start
[01-01 08:00:08.178 AV]: gz_framesource_in[    8.188395] vb is null, buf get:0x80000000 lastaddr = 0x00000000 idx=0 isp_index = 0
it IMP_FrameSource_CreateChn 0
[01-01 08:00:08.178 AV]: IMP_FrameSource_SetDirectModeAttr success! data_threshold = 1000
[01-01 08:00:08.178 AV]: gz_framesource_init IMP_FrameSource_CreateChn 1
[01-01 08:00:08.178 AV]: gz_framesource_init success
[01-01 08:00:08.179 AV]: gz_encoder_init start
[    8.238406] vb is null, buf get:0x80000000 lastaddr = 0x80000000 idx=0 isp_index = 0
i264e[info]: profile High, level 5.0
i264e[info]: profile High, level 2.2
[01-01 08:00:08.273 AV]: pstJpegeQl.user_ql_en = 0
[01-01 08:00:08.273 AV]: gz_encoder_init success
[01-01 08:00:08.274 AV]: gz_hal_video_init success
update_thread enter!
[01-01 08:00:08.278 AV]: gz_hal_led_init success! igpionum = 60
[01-01 08:00:08.278 AV]: hal_white_led_init success!
[01-01 08:00:08.279 AV]: gz_hal_led_init success! igpionum = 61
[01-01 08:00:08.279 AV]: hal_ir_led_init success!
[01-01 08:00:08.279 AV]: gz_video_input_init --------, Build (Sep 27 2024 17:16:27)
[01-01 08:00:08.280 AV]: gz_video_input_open +++[    8.321146] -----sc3332p_set_vflip: 974 val = 0x0, enable = 3
+++++
[01-01 08:00:08.280 AV]: gz_video_input_open channel: 0, encode: 0, res: 4
[01-01 08:00:08.280 AV]: gz_video_input_open bitrate: 1200, fps: 20, gop: 2
[370] s_video_context.video_conf[0].width = 2304
[371] s_video_context.video_conf[0].height = 1296
[01-01 08:00:08.280 AV]:  gz_hal_video_configure success
[01-01 08:00:08.280 AV]: gz_video_input_open --------
[01-01 08:00:08.281 AV]: gz_framesource_streamon IMP_FrameSource_EnableChn 0 : 0
[01-01 08:00:08.281 AV]: gz_hal_video_start 1450
[01-01 08:00:08.281 AV]: gz_hal_video_start 1458
[01-01 08:00:08.282 AV]: gz_video_input_start channel 0 ++++++++
[01-01 08:00:08.282 AV]: gz_video_input_start --------
[01-01 08:00:08.282 AV]: gz_video_input_open ++++++++
[01-01 08:00:08.282 AV]: gz_video_input_open channel: 1, encode: 0, res: 0
[01-01 08:00:08.282 AV]: gz_video_input_open bitrate: 256, fps: 20, gop: 2
[370] s_video_context.video_conf[1].width = 640
[371] s_video_context.video_conf[1].height = 360
[01-01 08:00:08.282 AV]:  gz_hal_video_configure success
[01-01 08:00:08.282 AV]: gz_video_input_open --------
[01-01 08:00:08.283 AV]: gz_framesource_streamon IMP_FrameSource_EnableChn 1 : 1
[01-01 08:00:08.283 AV]: gz_hal_video_start 1450
[01-01 08:00:08.283 AV]: gz_hal_video_start 1458
[01-01 08:00:08.283 AV]: gz_video_input_start channel 1 ++++++++
[01-01 08:00:08.283 AV]: gz_video_input_start --------
[01-01 08:00:08.284 AV]: gz_hal_video_set_inversion gz_hal_video_set_inversion enable: 1
[01-01 08:00:08.284 AV]: gz_hal_video_set_inversion IMP_ISP_Tuning_SetSensorHflip success, Hflipmode: 1
[01-01 08:00:08.284 AV]: gz_hal_video_set_inversion IMP_ISP_Tuning_SetSensorVflip success, Vflipmode: 1
[01-01 08:00:08.284 AV]: gz_hal_video_set_inversion success!
[01-01 08:00:08.285 AV]: gz_video_input_set_night_vision_mode mode: 0 ++++++++
[01-01 08:00:08.285 AV]: gz_video_input_set_night_vision_mode mode: 0 --------
[01-01 08:00:08.292 AV]: gz_video_input_set_osd time enable: 1, channel: 0, x: 1382, y: 25, format:1
[01-01 08:00:08.292 AV]: gz_video_input_set_osd pic enable: 0, channel: 0, x: 32, y: 20, path: /usr/bin/logo_main.bmp
[01-01 08:00:08.292 AV]: gz_hal_video_set_osd enter ! channel = 0
[01-01 08:00:08.292 AV]: gz_hal_video_set_isp_osd enter ! channel = 0
[01-01 08:00:08.293 AV]: begin to call IMP_ISP_Tuning_CreateOsdRgn!
[01-01 08:00:08.293 AV]: logo_width_align = 196, font_array[logo_idx].font_height = 70
[01-01 08:00:08.294 AV]: call IMP_ISP_Tuning_ShowOsdRgn success!
[01-01 08:00:08.294 AV]: gz_video_input_set_osd 677--------
[01-01 08:00:08.294 AV]: gz_video_input_set_osd time enable: 1, channel: 1, x: 374, y: 6, format:1
[01-01 08:00:08.294 AV]: gz_video_input_set_osd pic enable: 0, channel: 1, x: 10, y: 6, path: /usr/bin/logo_sub.bmp
[01-01 08:00:08.294 AV]: gz_hal_video_set_osd enter ! channel = 1
[01-01 08:00:08.294 AV]: rAttrFont.rect.p0.x = 374
[01-01 08:00:08.294 AV]: rAttrFont.rect.p0.y = 6
[01-01 08:00:08.294 AV]: rAttrFont.rect.p1.x = 637
[01-01 08:00:08.294 AV]: rAttrFont.rect.p1.y = 25
[01-01 08:00:08.294 AV]: osd_width_align = 264
[01-01 08:00:08.294 AV]: char_height = 20
[01-01 08:00:08.295 AV]: gz_video_input_set_osd 677--------
[01-01 08:00:08.297 AV]: gz_ai_start called !
head file version: 00000109, lib version: 00000109
[01-01 08:00:08.297 AV]: ingenic_ivs_personvehiclepetdet_start 216
[01-01 08:00:08.297 AV]: gz_ai_start 888
[01-01 08:00:08.297 AV]: gz_audio_input_open ++++++++, rate: 16000, bit: 16, volume: 96
[01-01 08:00:08.297 AV]: Set AEC Path Ok
[01-01 08:00:08.297 AV]: gz_hal_audio_in_config Audio in GetPubAttr samplerate:16000.
[01-01 08:00:08.297 AV]: gz_hal_audio_in_config Audio in GetPubAttr bitwidth:16.
[01-01 08:00:08.297 AV]: gz_hal_audio_in_config Audio in GetPubAttr soundmode:1.
[01-01 08:00:08.297 AV]: gz_hal_audio_in_config Audio in GetPubAttr frmNum:25.
[01-01 08:00:08.636 AV]: gz_hal_audio_in_config Audio in GetPubAttr numPerFrm:320.
[01-01 08:00:08.636 AV]: gz_hal_audio_in_config Audio in GetPubAttr chnCnt:1.
[01-01 08:00:08.298 AV]: pvirAddr = 0x75ae3300
INFO(jzdl): jzdl version:(00000000_659989c)  built:20240516-2035(5.4.0 c)
[01-01 08:00:08.684 AV]: gz_watchdog_feed success!
[    8.694136] [406] MOTOR_IRCUT_CLOSE! setdata = 0x0
[149]gz_hal_set_ircut_switch success! enable = 1
INFO(persondet): Ingenic DL PersonDet Promotion Version:0.1.9(00000109_111fcc8)  built:20240626-1938(5.4.0 simd)
param frameWidth: 640 frameHeight: 360  sense: -1 score: 0.400000 detdist: 3 det_size: 640 ptime: 0 count: 0 mod: 0 enable_perm: 0 enable_move: 1 track_mode: 0 observation_period: 5 active_count: 2 move_scale: 1.000000 move_sldwin_size: 2 sensor_size: 1 is_wide_angle: 112
[01-01 08:00:08.977 AV]: personvehiclepetdet_thread 416, ret = 0, sframe.size = 345600, sframe.virAddr = 0x0
prepare data
[01-01 08:00:09.100 AV]: Audio In GetChnParam usrFrmDepth : 20
warn: shm_init,53shm init already
[01-01 08:00:09.140 AV]: gz_hal_audio_in_config 576 IMP_AI_SetGain 31 return 0
[01-01 08:00:09.140 AV]: gz_hal_audio_in_config 594 IMP_AI_SetVol 80 return 0
[01-01 08:00:09.140 AV]: gz_audio_input_open ns mode default: 2
[1171] need to refresh display coordinates !
[01-01 08:00:09.278 AV]: gz_refresh_display_coordinates_isp success!
[01-01 08:00:09.278 AV]: gz_refresh_display_coordinates success!
[1181] refresh success !
[01-01 08:00:09.297 AV]: IMP_AI_EnableAlgo success !
[01-01 08:00:09.297 AV]: gz_audio_input_start ++++++++
[01-01 08:00:09.297 AV]: gz_hal_audio_in_open 783
[01-01 08:00:09.297 AV]: gz_hal_audio_in_open 790 [    9.313660] [406] MOTOR_IRCUT_CLOSE! setdata = 0x0

[01-01 08:00:09.297 AV]: gz_audio_input_start --------
[01-01 08:00:09.297 AV]: gz_audio_output_open sample rate: 16000, bit: 16, volume: 70
[01-01 08:00:09.299 AV]: Audio Out GetPubAttr samplerate:16000
[01-01 08:00:09.299 AV]: Audio Out GetPubAttr   bitwidth:16
[01-01 08:00:09.299 AV]: Audio Out GetPubAttr  soundmode:1
[01-01 08:00:09.299 AV]: Audio Out GetPubAttr     frmNum:5
[01-01 08:00:09.299 AV]: Audio Out GetPubAttr  numPerFrm:640
[01-01 08:00:09.299 AV]: Audio Out GetPubAttr     chnCnt:1
[149]gz_hal_set_ircut_switch success! enable = 0
[01-01 08:00:09.326 AV]: soft_photosensitive start !
[01-01 08:00:09.430 AV]: soft_photosensitive_thread ir mode set: -1 -> 0
warn: shm_init,53shm init already
[01-01 08:00:09.555 AV]: ai info 0: state|1| type|0| from |248 22| to |549 354| area:0.433733
[01-01 08:00:09.580 AV]: isetvol = 60
[01-01 08:00:09.580 AV]: gz_audio_output_open --------
[01-01 08:00:09.580 AV]: gz_audio_output_open sample rate: 16000, bit: 16, volume: 81
[01-01 08:00:09.580 AV]: gz_audio_output_open --------
[01-01 08:00:09.580 AV]: hal_white_led_set_onoff success! onoff = 0
[01-01 08:00:09.580 AV]: gz_dev_set_flood_light success! enable = 0
[01-01 08:00:09.684 AV]: gz_watchdog_feed success!
[01-01 08:00:09.721 AV]: gz_video_input_force_iframe channel ++++++++
[01-01 08:00:09.721 AV]: gz_video_input_force_iframe --------
[01-01 08:00:09.725 AV]: gz_video_input_force_iframe channel ++++++++
[01-01 08:00:09.725 AV]: gz_video_input_force_iframe --------
[01-01 08:00:09.771 AV]: gz_video_input_force_iframe channel ++++++++
[01-01 08:00:09.771 AV]: gz_video_input_force_iframe --------
[    9.834185] [406] MOTOR_IRCUT_CLOSE! setdata = 0x0
[149]gz_hal_set_ircut_switch success! enable = 0
[01-01 08:00:09.848 AV]: hal_ir_led_set_onoff success! onoff = 0
[01-01 08:00:09.848 AV]: hal_white_led_set_onoff success! onoff = 0
[01-01 08:00:09.848 AV]: soft_photosensitive to auto !
[01-01 18:12:15 TUYA D][tuya_ws_db.c:450] init fs. Path: /tmp/gz_etc/tuya/
[01-01 18:12:15 TUYA I][kv_storge.c:45] Init Kvs With File:/tmp/gz_etc/tuya/
[01-01 18:12:15 TUYA D][simplekv.c:945] path:/tmp/gz_etc/tuya/
[01-01 18:12:15 TUYA D][simplekv.c:981] get encrypt_key[▒▒▒US▒▒▒▒ykR▒▒]
[01-01 18:12:15 TUYA D][simplekv.c:999] normal file exist. bak file not exist
[01-01 18:12:15 TUYA D][simplekv.c:310] size in: 0 and final: 28700 And mag_rec_max: 512
[01-01 18:12:15 TUYA D][simplekv.c:325] create data hd success
[01-01 18:12:15 TUYA D][simplekv.c:1055] read from normal file
[01-01 18:12:15 TUYA D][simplekv.c:765] curr db is V2. No need to upgrade
[01-01 18:12:15 TUYA D][simplekv.c:555] head check success
[01-01 18:12:15 TUYA D][simplekv.c:658] read and check head success
[01-01 18:12:15 TUYA D][simplekv.c:1075] read from normal file success
[01-01 18:12:15 TUYA I][uni_thread.c:228] thread_create name:sys_timer,stackDepth:4096,totalstackDepth:4096,priority:5
[01-01 18:12:15 TUYA D][[   10.074170] [BT_DEV_INFO] bt_misc_dev_open:128
simplekv.c:1111] init from normal file success.
[01-01 18:12:15 TUYA I][mqc_app.c:350] mqc app[   10.085544] plat_soc:W]bsle_open_close_cmd, service[1], type[1].
 init ...
[01-01 18:12:15 TUYA I][uni_thread.c:228] thread_cre[   10.098283] [HCC] start hcc_adapt_bsle_msg_rx_proc,type:4,device_msg:0
[   10.109496] [HCC] Get bsle device action msg, type=[0]ity:4

[01-01 18:12:15 TUYA D][mqc_app.c:144] mq_pro:5 cnt:1
[01-01 [   10.120592] [BT_DEV_INFO]  ble btc open finish
18:12:15 TUYA D][mqc_app.c:144] mq_pro:31 cnt:2
[01-01 18:12:1[   10.130876] [HCC] ble set ble state ble_state 1
5 TUYA D][svc_online_log.c:295] svc online log init success
[01-01 18:12:15 TUYA E][log_seq.c:863] open err
[01-01 18:12:15 TUYA I][uni_thread.c:228] thread_create name:wk_th-0,stackDepth:[   10.153376] [BT_DEV_INFO]  ble open time:79
5120,totalstackDepth:13312,priority:3
[01-01 18:12:15 TUYA E][tuya_ipc_hardware_info.c:172] NO sensor info. Please check if you need.
[01-01 08:00:10.068 AV]: set led red -> 0
[01-01 08:00:10.068 AV]: set led blue -> 0
[01-01 08:00:10.068 AV]: set led green -> 2
[01-01 08:00:10.072 AV]: gz_ble_start ++++++++
[01-01 08:00:10.072 AV]: gz_hal_ble_start
[650] ble_uuid_server_init 1111 !
[659] ble_uuid_server_init 2222 !
[bts][info] btsrv_task_init btsrv_init: task create success
ble adapter init out nl_fd:22 epool_fd:23
[BT_APP] [ACore] ble gatt upper callback register add on module_id:00, event:0b
[BT_APP] [ACore] ble gatt upper callback register new on module_id:00, event:0b
[BT_APP] [ACore] ble gatt upper callback register new on module_id:00, event:0f
[BT_APP] [ACore] ble gatt upper callback register new on module_id:00, event:10
[BT_APP] [ACore] ble gatt upper callback register new on module_id:00, event:12
[BT_APP] [ACore] ble gatt upper callback register new on module_id:00, event:13
[BT_APP] [ACore] ble gatt upper callback register new on module_id:00, event:14
[BT_APP] [ACore] ble gatt upper callback register new on module_id:00, event:15
[BT_APP] [ACore] ble gatt upper callback register new on module_id:00, event:16
[BT_APP] [ACore] ble gatt upper callback register new on module_id:00, event:17
[BT_APP] [ACore] ble gatt upper callback register new on module_id:00, event:1a
[BT_APP] [ACore] ble gatt upper callback register add on module_id:03, event:07
[BT_APP] [ACore] ble gatt upper callback register new on module_id:03, event:07
[01-01 08:00:10.254 AV]: gz_video_input_set_night_vision_mode mode: 3 ++++++++
[01-01 08:00:10.255 AV]: gz_video_input_set_night_vision_mode mode: 3 --------
[01-01 08:00:10.290 AV]: soft_photosensitive_thread ir mode set: 0 -> 3
[BT_APP] [ACore] recover product type:0x00.
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0xc03 recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0x1002 recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] gaph hci command callback, operation=0, code:0[BT_APP] gaph hci command callback, operation=0, code:0[BT_APP] gaph hci command callback, operation=0, code:0[BT_APP] gaph hci command callback, operation=0, code:0[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0x1009 recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] [HCI] le local set own addr update adv pts_mode=0, is_le_ext_adving = 0, updated = 0[BT_APP] [HCI]le isa go idle local->leisa_cur = 00[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0x1003 recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0x2003 recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0xc01 recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0xc63 recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0x2001 recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0x200f recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0x201c recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0x2018 recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0x202a recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0x2024 recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0x203b recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0x2031 recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] [ACore] recover nv config:0x00.
[BT_APP] [ACore] recover system config:0x00.
[BT_APP] [ACore] recover key num:0x00.
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0x2005 recv success, unknown hci opcode stru[ACore] ble enable cbk in, event:b
[666] ble_uuid_server_init 3333 !
[01-01 08:00:10.392 AV]: gz_ble_start -------- 0
enable status: 0
[BT_APP] [ACore] ble gatt upper callback register new on module_id:03, event:01
[BT_APP] [ACore] ble gatt upper callback register new on module_id:03, event:03
[BT_APP] [ACore] ble gatt upper callback register new on module_id:03, event:05
[BT_APP] [ACore] ble gatt upper callback register new on module_id:03, event:09
[BT_APP] [ACore] ble gatt upper callback register new on module_id:03, event:08
[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf9c8
[BT_APP] ble general gatt add server server_handle:0xdaf9d0.
[BT_APP] [btsrv][INFO] service info[handle:1][is_prim:1][is_active: 0]
[BT_APP] [btsrv][INFO]uuid:1801
[BT_APP] [btsrv][INFO]CharInfo:[hdl:2][properties:0x22][permission:0x1]
[BT_APP] [btsrv][INFO]uuid:2A05
[BT_APP] [btsrv][INFO]desc_info:[desc_hdl:0x4][permission: 0x3]
[BT_APP] [btsrv][INFO]uuid:2902
[BT_APP] ble general gatt create se[   10.695652] [406] MOTOR_IRCUT_CLOSE! setdata = 0x0
rvice server_handle:0x0.[BT_APP] ble general gatt create service service_handle:0xdad6c0.
[BT_APP] [btsrv][INFO] btsrv gatts add characteristic handle:2
[BT_APP] ble general gatt add characteristic in service_handle:dad6c0, crt_handle:dad100.
[BT_APP] [btsrv][INFO] add character success, handle:2
[BT_APP] ble general gatt add descriptor characteristic_handle:77dc2a1c[BT_APP] ble general gatt add descriptor ok! crt_hdl:0xdad100.
[BT_APP] [btsrv][INFO] add descriptor handle:4
[BT_APP] gatt start service OK! serviceId = 0xdad6c0.
[BT_APP] [btsrv][INFO] btsrv gatts start service handle:1
[BT_APP] length: 10
[GAP service register][device name] handle: 0x0006, value handle: 0x0007
[GAP service register][device appearance] handle: 0x0008, value handle: 0x0009
[GAP service register][prefer conn param] handle: 0x000a, value handle: 0x000b
[BT_APP] [btsrv][INFO] service info[handle:5][is_prim:1][is_active: 0]
[BT_APP] [btsrv][INFO]uuid:1800
[BT_APP] [btsrv][INFO]CharInfo:[hdl:6][properties:0xa][permission:0x3]
[BT_APP] [btsrv][INFO]uuid:2A00
[BT_APP] [btsrv][INFO]CharInfo:[hdl:8][properties:0xa][permission:0x3]
[BT_APP] [btsrv][INFO]uuid:2A01
[BT_APP] [btsrv][INFO]CharInfo:[hdl:10][properties:0x2][permission:0x1]
[BT_APP] [btsrv][INFO]uuid:2A04
[BT_APP] [btsrv][INFO]CharInfo:[hdl:12][properties:0x2][permission:0x1]
[BT_APP] [btsrv][INFO]uuid:2AA6
[uuid server] ble uuid add service in
[uuid server] RX characters, server_id: 1, srv_handle: 14
[uuid server] characters uuid: fe a8
[uuid server] TX characters, server_id: 1, srv_handle: 14
[uuid server] characters uuid: fe a7
[BT_APP] [btsrv][INFO] service info[handle:14][is_prim:1][is_active: 0]
[BT_APP] [btsrv][INFO]uuid:FEE7
[BT_APP] [btsrv][INFO]CharInfo:[hdl:15][properties:0x8][permission:0x2]
[BT_APP] [btsrv][INFO]uuid:FEA8
[BT_APP] [btsrv][INFO]desc_info:[desc_hdl:0x11][permission: 0x3]
[BT_APP] [btsrv][INFO]uuid:2902
[BT_APP] [btsrv][INFO]CharInfo:[hdl:18][properties:0x10][permission:0x1]
[BT_APP] [btsrv][INFO]uuid:FEA7
[BT_APP] [btsrv][INFO]desc_info:[desc_hdl:0x14][permission: 0x3]
[BT_APP] [btsrv][INFO]uuid:2902
[uuid server] ble uuid add service out
[uuid server] init ok
[BT_APP] gatt server call back func event_type:0x2.
[BT_APP] ble general gatt start service result service_info.service_handle:1.
[BT_APP] [btsrv][INFO] start service success, handle:1
[BT_APP] ble general gatt create service server_handle:0x0.[BT_APP] ble general gatt create service service_handle:0xdad680.
[BT_APP] [btsrv][INFO] btsrv gatts add characteristic handle:6
[BT_APP] ble general gatt add characteristic in service_handle:dad680, crt_handle:dafed8.
[BT_APP] [btsrv][INFO] add character success, handle:6
[BT_APP] ble general gatt add characteristic in service_handle:dad680, crt_handle:daff90.
[BT_APP] [btsrv][INFO] add character success, handle:8
[BT_APP] ble general gatt add characteristic in service_handle:dad680, crt_handle:db0030.
[BT_APP] [btsrv][INFO] add character success, handle:10
[BT_APP] ble general gatt add characteristic in service_handle:dad680, crt_handle:db00e0.
[BT_APP] [btsrv][INFO] add character success, handle:12
[BT_APP] gatt start service OK! serviceId = 0xdad680.
[BT_APP] [btsrv][INFO] btsrv gatts start service handle:5
[BT_APP] gatt server call back func event_type:0x2.
[BT_APP] ble general gatt start service result service_info.service_handle:5.
[BT_APP] [btsrv][INFO] start service success, handle:5
[BT_APP] ble general gatt create service server_handle:0x0.[BT_APP] ble general gatt create service service_handle:0xdafc18.
[BT_APP] [btsrv][INFO] btsrv gatts add characteristic handle:15
[BT_APP] ble general gatt add characteristic in service_handle:dafc18, crt_handle:dafbb0.
[BT_APP] [btsrv][INFO] add character success, handle:15
[BT_APP] ble general gatt add descriptor characteristic_handle:77dc2914[BT_APP] ble general gatt add descriptor ok! crt_hdl:0xdafbb0.
[BT_APP] [btsrv][INFO] add descriptor handle:17
[BT_APP] ble general gatt add characteristic in service_handle:dafc18, crt_handle:db0288.
[BT_APP] [btsrv][INFO] add character success, handle:18
[BT_APP] ble general gatt add descriptor characteristic_handle:77dc2914[BT_APP] ble general gatt add descriptor ok! crt_hdl:0xdb0288.
[BT_APP] [btsrv][INFO] add descriptor handle:20
[BT_APP] gatt start service OK! serviceId = 0xdafc18.
[BT_APP] [btsrv][INFO] btsrv gatts start service handle:14
[BT_APP] gatt server call back func event_type:0x2.
[BT_APP] ble general gatt start service result service_info.service_handle:14.
[BT_APP] [btsrv][INFO] start service success, handle:14
[149]gz_hal_set_ircut_switch success! enable = 0
[01-01 08:00:11.067 AV]: hal_ir_led_set_onoff success! onoff = 0
[01-01 08:00:11.067 AV]: hal_white_led_set_onoff success! onoff = 0
[01-01 08:00:10.684 AV]: gz_watchdog_feed success!
[uuid server] start service cbk : server: 1 status: 0 srv_hdl: 1
[uuid server] start service cbk : server: 1 status: 0 srv_hdl: 5
[uuid server] start service cbk : server: 1 status: 0 srv_hdl: 14
all service start end, start adv
[ACore] ble set adv param min_interval:0x30, max interval:0x60, adv_type:0, duration:0
[ACore] ble set adv param, own addr:0x00:**:**:**:00:00
[ACore] ble set adv param, peer addr:0x00:**:**:**:00:00
[ACore] gap ble start adv in, adv_id:1
[BT_APP] ble log: ble general set extended adv param g_adv_addr_type = 0 adv_event_flag = 0,g_config_le_slave_use_privacy = 0
set_adv_data cbk, adv_id: 1, status: 0
set_adv_param cbk, adv_id: 1, status: 0
[BT_APP] [HCI]le local set own addr by type addr_type = 00[BT_APP] [HCI]le local get own addr by type slot = 00, type = 00[BT_APP] [HCI]le local get own addr by type slot = 00, type = 00[BT_APP] [GAP]gaph le manager cmd send set ext adv param own_address_type = 0 adv_event_flag = 0[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0x2036 recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf918
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0x2035 recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdafbf8
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0x2037 recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdad4d8
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0x2038 recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdaf918
[BT_APP] [HCI][STREAM_TO_STRUCT] OPCODE=0x2039 recv success, unknown hci opcode stru[BT_APP] [TIMER_DEL][STACK_TIMER] TIMER=0xdafbf8
adv enable adv_id: 1, status:1
[01-01 08:00:12.068 AV]: gz_watchdog_feed success!


```


**U-boot magic files:**

```

FIRMWARE_C5L-2_F.bin
FIRMWARE_C5L-2.bin
demo.bin

```

**cat /proc/mtd:**
```

```

**cat /proc/version:**

``


**lsmod:**

```

```


**dmesg:**

```


```

**ps:**

```

```

**mount -t debugfs none /sys/kernel/debug; cat /sys/kernel/debug/gpio:**

```

```


**/etc/init.d/rcS:**

```

```

**/etc/inittab:**

```

```

**/etc/sync.ini:**

```

```
