## v1.0.0 - 2018-09-06

* Package.json: Add private: true to stop publishing to npm [Trong Nghia Nguyen]
* Device: Add new contract for Revolution Pi Core 3 [Trong Nghia Nguyen]
* Device: Add new contract for Stem x86 32bit [Trong Nghia Nguyen]
* Qemu: Update qemu to v3.0.0+resin [Trong Nghia Nguyen]

## v1.1.2 - 2018-10-23

* Contracts: various small updates [Trong Nghia Nguyen]
* Openjdk: Add contracts and partials for OpenJDK stack [Trong Nghia Nguyen]
* Golang: Add contract and partials for golang stack [Trong Nghia Nguyen]
* Python: Add contract and partials for Python stack [Trong Nghia Nguyen]
* Namechange: Change xbuild partial to balena-xbuild [Trong Nghia Nguyen]
* Partials: Few partial updates for node stack [Trong Nghia Nguyen]
* Version: Add latest version for some contracts [Trong Nghia Nguyen]
* Balena-xbuild: Change resin-xbuild to balena-xbuild [Trong Nghia Nguyen]
* Entry-script: Update entry script contract for balena base images [Trong Nghia Nguyen]
* Debian: Drop support for Debian Wheezy [Trong Nghia Nguyen]
* Node: Add contracts and partials for nodejs base image stack [Trong Nghia Nguyen]
* Os: Remove tini and initsystem related partials [Trong Nghia Nguyen]
* Blob: Remove tini contracts [Trong Nghia Nguyen]
* Os: add install_packages script to os partials [Trong Nghia Nguyen]
* Os: Update default env vars [Trong Nghia Nguyen]

## v1.1.1 - 2018-10-23

* Base-images: Add deprecation warning when using resin base images [Trong Nghia Nguyen]

## v1.1.0 - 2018-09-25

* Device: Add contract for asus-tinker-board and asus-tinker-board-s [Trong Nghia Nguyen]

* Base-image: Specify package repository when installing default packages [Trong Nghia Nguyen]
* Device: add contract for new device - CTI Spacely TX2 [Trong Nghia Nguyen]
* Add contract for new device: CTI Orbitty TX2 [Trong Nghia Nguyen]
* Add rpi and armv7hf to the supported architecture list of Alpine Linux. They are identical (based on arm32v6/alpine) but kept separate to support mixed-device fleet. [Trong Nghia Nguyen]
* Remove armhf from architecture contracts (Only keeps what /config endpoint returns). [Trong Nghia Nguyen]
* Add contract and partials for ubuntu. [Trong Nghia Nguyen]
* Add artik530 contract to hw.device-type. [Trong Nghia Nguyen]
* Add artik533s contract to hw.device-type. [Trong Nghia Nguyen]
* Add fincm3 contract to hw.device-type. [Trong Nghia Nguyen]
* Add orangepi-plus2 contract to hw.device-type. [Trong Nghia Nguyen]
* Add bananapi-m1-plus contract to hw.device-type [Horia Delicoti]