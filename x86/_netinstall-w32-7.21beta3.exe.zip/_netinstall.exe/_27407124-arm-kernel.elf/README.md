### 27407124-arm-kernel.elf
#### Identification (`file <*>`):
```
ELF 32-bit LSB executable, ARM, EABI5 version 1 (SYSV), statically linked, stripped
```
#### Analysis (`binwalk <*>`):
```

DECIMAL       HEXADECIMAL     DESCRIPTION
--------------------------------------------------------------------------------
0             0x0             ELF, 32-bit LSB executable, ARM, version 1 (SYSV)
77292         0x12DEC         xz compressed data
77324         0x12E0C         xz compressed data
2788876       0x2A8E0C        xz compressed data
3442445       0x34870D        ZBOOT firmware header, header size: 32 bytes, load address: 0x12412B44, start address: 0xC0384AE1, checksum: 0x7CD87CDC, version: 0x0668300D, image size: 1621968817 bytes
```
#### Listing (`ls -AlR --time-style=full-iso <*>`):
```
/:
total 7836
-rw-r--r-- 1 root root 11022304 2025-10-16 16:37:49.073790864 +0100 12e0c.vmlinux
```

