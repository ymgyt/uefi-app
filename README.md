# uefi handson

handson of https://gil0mendes.io/blog/an-efi-app-a-bit-rusty/ on Mac OS

## Prerequisites

* QEMU (`brew install qemu`)
* python3
* `rustup component add rust-src --toolchain nightly`
* nightly rust
```
rustc -V
rustc 1.53.0-nightly (07e0e2ec2 2021-03-24)
```


## Usage

```
./build.py build && ./build.py run
```
