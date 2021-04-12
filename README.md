# pactest

Do you frequently test software but forget to uninstall it, or want to use software without it adding or removing files from your system? This script creates a chroot for you to test software from the AUR in.

# Installation

Use your preferred AUR helper to install `pactest-git`

```sh
paru -S pactest-git
```

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
pactest -c
```
