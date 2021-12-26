# hxp_trusty_user_diary
HXPCTF Trusty User Diary exploit &amp; writeup

### OUTPUT

```bash
~ $ 
~ $ id
uid=1000(ctf) gid=1000 groups=1000
~ $ /exploit 
Busybox page allocated at : 0x7f2e69c17000
Mapped pages allocated at : 0x7f2e69c16000
Written shellcode...
Simply type 'exit' and enter
~ $ exit
hxp{FLAG}
hxp{FLAG}
hxp{FLAG}
[   11.390405] Kernel panic - not syncing: Attempted to kill init! exitcode=0x00000100
[   11.391145] CPU: 0 PID: 1 Comm: init Tainted: G           OE     5.15.4 #1
[   11.391602] Hardware name: QEMU Standard PC (i440FX + PIIX, 1996), BIOS rel-1.14.0-27-g64f37cc530f1-prebuilt.qemu.or4
[   11.392373] Call Trace:
```
