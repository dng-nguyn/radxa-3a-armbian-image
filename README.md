Personal build for Radxa ROCK 3A with armbian build tools

Date: 2024-09-15

Vendor:         Armbian-unofficial

Revision:       24.11.0-trunk

Board:          Rock-3a

Kernel:         Linux 6.1.75 (vendor)

Sources:        https://github.com/armbian/build

Sources rev:    cbc7982

Build options used:
```sh
./compile.sh build BOARD=rock-3a BRANCH=vendor BUILD_DESKTOP=no BUILD_MINIMAL=yes KERNEL_CONFIGURE=no RELEASE=bookworm INSTALL_HEADERS=yes DISABLE_IPV6=false ROOTFS_TYPE=ext4
```
