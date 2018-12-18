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
