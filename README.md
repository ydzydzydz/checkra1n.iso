## checkra1n.iso



The live CD for checker1n build from CentOS 7

- [x] Legacy BIOS
- [x] UEFI

> username: root
>
> password: zz



```bash
wget -o /root/checkra1n https://assets.checkra.in/downloads/linux/cli/x86_64/xxxx/checkra1n
yum -y install livecd-tools
livecd-creator -c checkra1n.cfg -f checkra1n-0.11.0-by-zhuangzhuang -d
ls -l checkra1n-0.11.0-zhuangzhuang.iso
```

