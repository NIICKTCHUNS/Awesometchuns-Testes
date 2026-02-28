# Como adicionar o Kernel Linux do CachyOS (AUR) no UEFI com EFIStub e efibootmgr   
***Depois de muito sofrimento e quebração de cabeça***   
```
sudo efibootmgr --create --disk /dev/nvme0n1 --part 1 --label "Arch Linux (Cachy)" --loader /vmlinuz-linux-cachyos --unicode 'root=UUID=18d65d07-54f2-4898-9721-76da14506b91 zswap.enabled=0 rootflags=subvol=@ rw rootfstype=btrfs initrd=\initramfs-linux-cachyos.img'

```
Fontes:   
[EFI boot sub](https://wiki.archlinux.org/title/EFI_boot_stub)   
[Persistent block device naming](https://wiki.archlinux.org/title/Persistent_block_device_naming) \| [Seção 1.2](https://wiki.archlinux.org/title/Persistent_block_device_naming#by-uuid)   
[EFI system partition](https://wiki.archlinux.org/title/EFI_system_partition)   
   
