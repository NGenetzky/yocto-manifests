
# Yocto Manifests

## Getting Started

### Install repo

[git-repo](https://code.google.com/archive/p/git-repo/)

### Initalize repos

    # The current directory will be the TOP_DIR of the repo.
    repo init \
        --manifest-url=git://github.com/ngenetzky/yocto-manifests.git \
        --groups=poky

## Groups

### poky

DISTRO="poky"

### rpi

BBLAYERS+="meta-raspberrypi"

