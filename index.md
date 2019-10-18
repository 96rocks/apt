# apt.96rocks.com
Debian packages for rockchip 96boards.

# Usage
For Debian stretch:

    export dist=stretch

For Ubuntu bionic:

    export dist=bionic

Add the repository with the following command:

    echo "deb http://apt.96rocks.com/${dist}/ ${dist} main" | sudo tee /etc/apt/sources.list.d/apt-96rocks.list

Get the pub key

    wget -O -  apt.96rocks.com/${dist}/public.key | sudo apt-key add -

then run

    sudo apt-get update && sudo apt-get upgrade
    sudo apt-get install *package-name*

# Available packages

## Bionic

96boards-tools-common

ap6255-firmware

ap6256-firmware

ap6356-firmware

brcm-patchram-plus1-32

brcm-patchram-plus1-64

gstreamer1.0-rockchip1

gstreamer1.0-rockchip1-extra

librockchip-mpp1

linux-4.4-latest

linux-firmware-image-4.4.154-59-rockchip-g5e70f14

linux-firmware-image-4.4.154-72-rockchip-g6520deb

linux-firmware-image-4.4.154-73-rockchip-00007-g155a65a

linux-firmware-image-4.4.154-83-rockchip-00023-gae7a309

linux-headers-4.4.154-59-rockchip-g5e70f14

linux-headers-4.4.154-72-rockchip-g6520deb

linux-headers-4.4.154-73-rockchip-00007-g155a65a

linux-headers-4.4.154-83-rockchip-00023-gae7a309

linux-image-4.4.154-59-rockchip-g5e70f14

linux-image-4.4.154-72-rockchip-g6520deb

linux-image-4.4.154-73-rockchip-00007-g155a65a

linux-image-4.4.154-83-rockchip-00023-gae7a309

mpv

opencv4.0

rev3328-rk-u-boot-latest

rev3328-rk-ubootimg

rock960ab-rk-u-boot-latest

rock960ab-rk-ubootimg

rock960c-rk-u-boot-latest

rock960c-rk-ubootimg

rockchip-fstab

rockchip-mali-midgard-dev

rockchip-mali-midgard14

rockchip-overlay

## Stretch

96boards-tools-common

ap6255-firmware

ap6256-firmware

ap6356-firmware

brcm-patchram-plus1-32

brcm-patchram-plus1-64

gstreamer1.0-rockchip1

gstreamer1.0-rockchip1-dbgsym

gstreamer1.0-rockchip1-extra

gstreamer1.0-rockchip1-extra-dbgsym

libgstreamer-plugins-bad1.0-0

libmali-rk-dev

libmali-rk-midgard-t76x-r14p0-r0p0

libmali-rk-midgard-t76x-r14p0-r0p0-wayland

libmali-rk-midgard-t76x-r14p0-r1p0

libmali-rk-midgard-t86x-r14p0

libmali-rk-utgard-400-r7p0

libmali-rk-utgard-450-r7p0

librockchip-mpp-dev

librockchip-mpp-static

librockchip-mpp1

librockchip-mpp1-dbgsym

librockchip-vpu0

librockchip-vpu0-dbgsym

linux-4.4-latest

linux-firmware-image-4.4.154-59-rockchip-g5e70f14

linux-firmware-image-4.4.154-72-rockchip-g6520deb

linux-firmware-image-4.4.154-73-rockchip-00007-g155a65a

linux-firmware-image-4.4.154-83-rockchip-00023-gae7a309

linux-headers-4.4.154-59-rockchip-g5e70f14

linux-headers-4.4.154-72-rockchip-g6520deb

linux-headers-4.4.154-73-rockchip-00007-g155a65a

linux-headers-4.4.154-83-rockchip-00023-gae7a309

linux-image-4.4.154-59-rockchip-g5e70f14

linux-image-4.4.154-72-rockchip-g6520deb

linux-image-4.4.154-73-rockchip-00007-g155a65a

linux-image-4.4.154-83-rockchip-00023-gae7a309

mpv

opencv4.0

rev3328-rk-u-boot-latest

rev3328-rk-ubootimg

rock960ab-rk-u-boot-latest

rock960ab-rk-ubootimg

rock960c-rk-u-boot-latest

rock960c-rk-ubootimg

rockchip-fstab

rockchip-mali-midgard-dev

rockchip-mali-midgard14

rockchip-mpp-demos

rockchip-mpp-demos-dbgsym

rockchip-overlay
