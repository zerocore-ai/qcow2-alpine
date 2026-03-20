# qcow2-alpine

Alpine Linux v3.23 qcow2 disk images.

- **Base**: Alpine Linux 3.23.3
- **Filesystem**: ext4
- **Disk format**: qcow2
- **Virtual size**: 64 MiB

## Images

| File | Arch |
|------|------|
| `aarch64.qcow2` | ARM 64-bit |
| `x86_64.qcow2` | x86 64-bit |

## Usage

```sh
# use a specific arch image as a block root
/path/to/qcow2-alpine/aarch64.qcow2
/path/to/qcow2-alpine/x86_64.qcow2
```
