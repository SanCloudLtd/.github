# Open Source @ SanCloud Ltd

[<img align=right src="https://www.sancloud.co.uk/wp-content/uploads/2016/09/sancloud_and_address_web.png">](https://www.sancloud.com/)

Open Source software is a fundamental part of the work we do at
[SanCloud](https://www.sancloud.com/).
Here you will find open source projects maintained by SanCloud
as well as some of our contributions to other projects.
For any queries related to the use of Open Source at SanCloud
please contact us by email to <opensource@sancloud.com>.

## Open Source Projects on GitHub

* The Board Support Package (BSP) for SanCloud hardware
  is developed here on GitHub.
  It consists of the following components:

  * [meta-sancloud](https://github.com/SanCloudLtd/meta-sancloud)
    BSP layer for use with [Yocto Project](https://www.yoctoproject.org/).
    This is the place to start
    if you wish to build custom software images
    for the BeagleBone Enhanced (BBE).

  * [Linux kernel](https://github.com/SanCloudLtd/linux)
    with SanCloud patches.
    This repository contains LTS branches of the Linux kernel
    with improved support for SanCloud hardware, along with
    in-development code for submission to the mainline kernel.

  * [U-boot](https://github.com/SanCloudLtd/u-boot)
    with SanCloud patches.
    This repository contains improved U-boot support for SanCloud hardware,
    along with in-development code for submission upstream.

  * [qcacld2](https://github.com/SanCloudLtd/qcacld-2.0) drivers and
    [firmware](https://github.com/SanCloudLtd/firmware).

* Other projects:

  * [Container images](https://github.com/orgs/SanCloudLtd/packages?ecosystem=container)
    (and [sources](https://github.com/SanCloudLtd/containers))
    which can be used to build software for the BBE.

  * [bitbangrelay](https://github.com/SanCloudLtd/bitbangrelay),
    a simple tool for controlling USB relay boards based around an
    FTDI FT232R/FT245R chip in bitbang mode.

## Other Open Source Projects

In addition to the Open Source projects hosted here on GitHub,
SanCloud participates in the
[Automotive Grade Linux (AGL)](https://www.automotivelinux.org/)
Linux Foundation project
to support the use of SanCloud hardware in automotive and related deployments.

## Reference Material

The [BeagleBone Enhanced (BBE) schematics](https://github.com/SanCloudLtd/BeagleBoneEnhanced)
are published here on GitHub for reference.
