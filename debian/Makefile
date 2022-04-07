.PHONY: vendor

SHELL=/bin/bash # Use bash syntax

release:
	cd ${OS_RELEASE}; reprepro -P 1  -S main includedeb ${OS_RELEASE} ${DEB_FILE}

release-lomocloud-buster: OS_RELEASE=buster
release-lomocloud-buster: DEB_FILE=../../lomo-cloud.deb
release-lomocloud-buster: release

release-vips-armv7hf-buster: OS_RELEASE=buster
release-vips-armv7hf-buster: DEB_FILE=../../lomo-vips_armv7hf_debian_buster.deb
release-vips-armv7hf-buster: release

release-vips-aarch64-buster: OS_RELEASE=buster
release-vips-aarch64-buster: DEB_FILE=../../lomo-vips_aarch64_debian_buster.deb
release-vips-aarch64-buster: release

release-vips-amd64-focal: OS_RELEASE=focal
release-vips-amd64-focal: DEB_FILE=../../lomo-vips_amd64_ubuntu_focal.deb
release-vips-amd64-focal: release

release-vips-amd64-groovy: OS_RELEASE=groovy
release-vips-amd64-groovy: DEB_FILE=../../lomo-vips_amd64_ubuntu_groovy.deb
release-vips-amd64-groovy: release

release-lomod-armv7hf-buster: OS_RELEASE=buster
release-lomod-armv7hf-buster: DEB_FILE=../../lomod_armv7hf_debian_buster.deb
release-lomod-armv7hf-buster: release

release-lomod-aarch64-buster: OS_RELEASE=buster
release-lomod-aarch64-buster: DEB_FILE=../../lomod_aarch64_debian_buster.deb
release-lomod-aarch64-buster: release

release-lomod-amd64-focal: OS_RELEASE=focal
release-lomod-amd64-focal: DEB_FILE=../../lomod_amd64_ubuntu_focal.deb
release-lomod-amd64-focal: release

release-lomod-amd64-groovy: OS_RELEASE=groovy
release-lomod-amd64-groovy: DEB_FILE=../../lomod_amd64_ubuntu_groovy.deb
release-lomod-amd64-groovy: release

release-tflite-armv7hf-buster: OS_RELEASE=buster
release-tflite-armv7hf-buster: DEB_FILE=../../tensorflow_armhf_2.6.0.deb
release-tflite-armv7hf-buster: release

release-tflite-aarch64-buster: OS_RELEASE=buster
release-tflite-aarch64-buster: DEB_FILE=../../tensorflow_arm64_2.6.0.deb
release-tflite-aarch64-buster: release

release-tflite-amd64-buster: OS_RELEASE=buster
release-tflite-amd64-buster: DEB_FILE=../../tensorflow_amd64_2.6.0.deb
release-tflite-amd64-buster: release

release-tflite-amd64-focal: OS_RELEASE=focal
release-tflite-amd64-focal: DEB_FILE=../../tensorflow_amd64_2.6.0.deb
release-tflite-amd64-focal: release

