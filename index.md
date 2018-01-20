---
layout: page
title: A full Linux system for your phone / tablet
---

### What's the Plan?

![](/img/scorpion_plasma.png){:width="50%"}
![](/img/yuga_plasma_mobile.jpg){:width="45%"}
Basically ... this.

Well, of course this picture is faked, but seeing this in reality it's not far away.

I'm quite successfully working on making debian work on top of Halium.
Halium allows running GNU/Linux on Android devices by using Androids drivers in the absence of real open-source drivers.
Of course once mainline support is available, debian can of course run on top of the mainline kernel on those devices.

### What has already been done:

* Packaging Plasma Mobile
    * kwin-hwcomposer backend
    * plasma-phone-components
    * plasma settings
* Packaging libhybris
* Set up initial binary repository
* Release first working rootfs builds

### What still needs to be done:

* Make one libhybris-build compatible with caf and non-caf devices and multiple android versions at the same time
* Build all packages
* Test
* Get all packages into debian

### Non-graphical development rootfs builds

[Available on github](https://github.com/debian-pm-tools/rootfs-builder/releases)
