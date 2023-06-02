
### How to build

- Step 1.Install Software Package

```bash
$ ./01_denos_pre_reqs.sh
```

- Step 2.Make rootfs

```bash
$ ./02_denos_debootstrap.sh
```

- Step 3.Install Distro in chroot

Example：xfce desktop.

```bash
$ ./03_denos_chroot_xfce.sh
```

- Step 4.Make squashfs

```bash
$ ./04_04_denos_MakeSquashfs.sh
```

- Step 5.Generate ISO

```bash
$ ./05_denos_BiosUEFI_ISO.sh
```
