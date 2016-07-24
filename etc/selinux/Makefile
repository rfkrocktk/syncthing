#!/usr/bin/make -f

all: build

build:
	@make NAME=syncthing -f /usr/share/selinux/devel/Makefile DISTRO=f24

install: build
	sudo semodule -i syncthing.pp
