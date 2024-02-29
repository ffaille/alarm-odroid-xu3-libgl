This repository hosts [alarm/odroid-xu3-libgl](https://github.com/archlinuxarm/PKGBUILDs/blob/master/alarm/odroid-xu3-libgl/PKGBUILD) PKGBUILD. It allows you to build the odroid-xu3-libgl package which provides the Mali GL driver for the ODROID XU3/XU4/HC1/HC2/MC1 (vr17p0-01rel0 from Hardkernel).

The goal of this project is to offer an up-to-date version while remaining as close as possible to the productions of the official maintainer. Maybe this code can be pushed into the official repository later...

Tested with XU4 only (don't have XU3/HC1/HC2/MC1). Work in progress. Feedback is welcome.

## Usage
* sudo pacman -S base-devel git
* git clone https://github.com/ffaille/alarm-odroid-xu3-libgl.git
* cd alarm-odroid-xu3-libgl
* makepkg --syncdeps --noconfirm --log
* sudo pacman -U ./odroid-xu3-libgl-r17p0-2-armv7h.pkg.tar.xz