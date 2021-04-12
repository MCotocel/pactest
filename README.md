# pactest
Test AUR software in a chroot

## Usage

Setup chroot

```sh
pactest -s
```

Install software in chroot

```sh
pactest -i example
```

Execute software in chroot

```sh
pactest -x example
```

Delete chroot

```sh
pactest -d
```

Chroot into chroot

```sh
pactest -s
```
