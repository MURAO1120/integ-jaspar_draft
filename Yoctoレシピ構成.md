# Structure

## Core Poky Layers

| Layer              | Path                | Description                                      | Version                   | Remote URL                                      |
|-------------------|---------------------|--------------------------------------------------|---------------------------|-------------------------------------------------|
| meta              | /poky/meta          | Yocto Project core metadata layer                | refs/tags/scarthgap-5.0.8 | https://github.com/yoctoproject/poky           |
| meta-poky         | /poky/meta-poky     | Poky-specific configuration and policies         | refs/tags/scarthgap-5.0.8 | https://github.com/yoctoproject/poky           |
| meta-yocto-bsp    | /poky/meta-yocto-bsp| Reference BSPs provided by Yocto Project         | refs/tags/scarthgap-5.0.8 | https://github.com/yoctoproject/poky           |

## Poky Development Support Layers

| Layer           | Path                    | Description                                      | Version                   | Remote URL                                      |
|----------------|-------------------------|--------------------------------------------------|---------------------------|-------------------------------------------------|
| meta-selftest  | /poky/meta-selftest     | Yocto Project self-test layer for validation     | refs/tags/scarthgap-5.0.8 | https://github.com/yoctoproject/poky           |
| meta-skeleton  | /poky/meta-skeleton     | Template recipes for creating new packages       | refs/tags/scarthgap-5.0.8 | https://github.com/yoctoproject/poky           |


## Additonal Layer

| Layer | Path | Description | Version | Remote URL |
|-------|------|-------------|---------|------------|
| **meta-jaspar** | `/poky/meta-jaspar` | JASPAR SDV Development support layer | `main` | https://github.com/jaspar-sdv-dev/meta-jaspar |
| **meta-openembedded** | `/poky/meta-openembedded` | Additional OpenEmbedded function layer | `scarthgap` | https://github.com/openembedded/meta-openembedded |
| **meta-virtualization** | `/poky/meta-virtualization` | Virtualization features Enable layer | `scarthgap` | https://git.yoctoproject.org/meta-virtualization |
| **meta-raspberrypi** | `/poky/meta-raspberrypi` | Raspberry Pi support layer | `scarthgap` | https://git.yoctoproject.org/meta-raspberrypi |
| **meta-agl** | `/poky/meta-agl` | Automotive Grade Linux features layer | `salmon` | https://gitlab.com/automotivegradelinux/AGL/meta-agl |
