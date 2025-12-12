Clone the repository
```
git clone https://gitlab.archlinux.org/archlinux/packaging/packages/linux.git build
cd build
```

Edit the PKGBUILD and config files with your editor of choice, for example:
```
hx PKGBUILD
hx config
```

Add whichever options you want (to remove initramfs):
```
CONFIG_BLK_DEV_NVME=y
CONFIG_NVME_CORE=y
CONFIG_SCSI=y
CONFIG_BLK_DEV_SD=y
CONFIG_ATA_ACPI=y
CONFIG_SATA_PMP=y
CONFIG_SATA_AHCI=y
CONFIG_ATA_BMDMA=y
CONFIG_ATA_SFF=y
CONFIG_ATA_PIIX=y
CONFIG_EXT4_FS=y
CONFIG_MSDOS_PARTITION=y
CONFIG_PARTITION_ADVANCED=y
CONFIG_EFI_PARTITION=y
```

Build the package:
```
makepkg -s --skippgpcheck
# we skip pgp because it dosen't work otherwise
```

