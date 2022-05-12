### 安装前准备
下载archlinux的livecd，理论上使用manjaro的livecd或许也可以
### EFISTUB
```shell
pacman -S efibootmgr
efibootmgr --disk /dev/nvme0n1p1 --part 1 --create --label "Arch Linux" --loader /vmlinuz-linux-lts --unicode 'root=PARTUUID=fcad510d-7553-4565-a458-c4a952f0eb9e rw initrd=\initramfs-linux-lts.img' --verbose
```

