# usbutils for OSX

usbutils fork from https://github.com/veltzer/usbutils

## changes

* Mac OSX 10.6.8 works
* use latest usb.ids from http://www.linux-usb.org/usb.ids

## requirement

* Mac OS X 10.6 and above version (10.8 beta not tested)

## How to compile

 	first get usbhid-dump:
   		git submodule init
		git submodule update
 	initialize autobuild with:
		autoreconf --install --symlink
 	configure with:
		./configure
 	build with:
		make

## Usage Sample: 

	command: ./lsusb 
	output:
	Bus 004 Device 001: ID 05ac:8005 Apple, Inc. 
	Bus 004 Device 002: ID 05ac:8242 Apple, Inc. IR Receiver [built-in]
	Bus 004 Device 003: ID 05ac:0236 Apple, Inc. Internal Keyboard/Trackpad (ANSI)
	Bus 004 Device 004: ID 093a:2510 Pixart Imaging, Inc. Optical Mouse
	Bus 036 Device 001: ID 05ac:8006 Apple, Inc. 
	Bus 036 Device 002: ID 05ac:8507 Apple, Inc. Built-in iSight
	Bus 006 Device 001: ID 05ac:8005 Apple, Inc. 
	Bus 038 Device 001: ID 05ac:8006 Apple, Inc.

## About

twitter: [@othercatlee](twitter.com/#!/othercatlee)


