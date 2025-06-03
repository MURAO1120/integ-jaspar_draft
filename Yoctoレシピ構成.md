# Yocto Recipe Structure

| Layer | Path | Description | Version | Remote URL |
|-------|------|-------------|---------|------------|
| **yoctoproject/poky** | `/poky` | Yocto Project core component layer | `refs/tags/scarthgap-5.0.8` | https://github.com/yoctoproject/poky |
| **jaspar-sdv-dev/meta-jaspar** | `/poky/meta-jaspar` | JASPAR SDV Development support layer | `main` | https://github.com/jaspar-sdv-dev/meta-jaspar |
| **openembedded/meta-openembedded** | `/poky/meta-openembedded` | Additional OpenEmbedded function layer | `scarthgap` | https://github.com/openembedded/meta-openembedded |
| **meta-virtualization** | `/poky/meta-virtualization` | Virtualization features Enable layer | `scarthgap` | https://git.yoctoproject.org/meta-virtualization |
| **meta-raspberrypi** | `/poky/meta-raspberrypi` | Raspberry Pi support layer | `scarthgap` | https://git.yoctoproject.org/meta-raspberrypi |
| **automotivegradelinux/AGL/meta-agl** | `/poky/meta-agl` | Automotive Grade Linux features layer | `salmon` | https://gitlab.com/automotivegradelinux/AGL/meta-agl |
