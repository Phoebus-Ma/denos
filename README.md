## denos

Automatically build Linux distributions.


### How to build

- 1.Install Software Package

```bash
./01_denos_pre_reqs.sh
```

- 2.Make rootfs

```bash
./02_denos_debootstrap.sh
```

- 3.Install Distro in chroot

Example：xfce desktop.

```bash
./03_denos_chroot_xfce.sh
```

- 4.Make squashfs

```bash
./04_04_denos_MakeSquashfs.sh
```

- 5.Generate ISO

```bash
./05_denos_BiosUEFI_ISO.sh
```
