FROM balenalib/amd64-fedora:26-build
LABEL io.balena.device-type="up-core-plus"

RUN dnf install -y \
		less \
		nano \
		net-tools \
		usbutils \
		gnupg \
		i2c-tools \
	&& dnf clean all