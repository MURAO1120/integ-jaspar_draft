# Yocto Recipe Structure

| Layer | Path | Description | Version | Remote URL |
|-------|------|-------------|---------|------------|
| **yoctoproject/poky** | `/poky` | Core component of the Yocto Project layer. | `refs/tags/scarthgap-5.0.8` | [https://github.com/yoctproject/poky |
| **jaspar-sdv-dev/meta-jaspar** | `/poky/meta-jaspar` | Development support for JASPAR SDV in this layer. | `main` | [https://github.com/jaspar-sdv-dev/meta-jasar |
| **openembedded/meta-openembedded** | `/poky/meta-openembedded` | Provides additional OpenEmbedded functionality layer. | `scarthgap` | https://github.com/openembedded/meta-openembedded |
| **meta-virtualization** | `/poky/meta-virtualization` | Enables virtualization features through this layer. | `scarthgap` | https://git.yoctoproject.org/meta-virtualization |
| **meta-raspberrypi** | `/poky/meta-raspberrypi` | Adds Raspberry Pi support via this layer. | `scarthgap` | https://git.yoctoproject.org/meta-raspberrypi |
| **automotivegradelinux/AGL/meta-agl** | `/poky/meta-agl` | Implements Automotive Grade Linux features in this layer. | `salmon` | https://gitlab.com/automotivegradelinux/AGL/meta-agl |
