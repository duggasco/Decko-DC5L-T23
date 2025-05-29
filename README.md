
Shop link: [https://www.amazon.com/dp/B0DFLJHQ2Q](https://www.amazon.com/dp/B09GK7RHSM)
Model: DC5L
PTZ: no
Onvif: Yes
CPU: T23
Sensors: TBD
Wireless: BL-M35343XU1

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

```

 

**U-boot magic files:**


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
