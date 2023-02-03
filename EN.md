# How to change the distro?


## First of all, what we need;

* USB

* Computer

* Information

## Download Process

* We download distributions from certain sites. Download sites of some distributions; (Click on the distribution and you will access the download site. If that distribution is not in the list, you can write it to Google.)

[Ubuntu](https://ubuntu.com/download/desktop)

[Linux Mint](https://linuxmint.com)

[EndeavourOS](https://endeavouros.com)

## Burn ISO to USB;

* Previously;

Let's type lsblk and find our usb. Copy the code at the beginning when you find it.

* Then let's write:

$ sudo dd if=archlinux-2017.iso of=/dev/ status=progress

* Let's paste the usb code there after /dev/. Then let's show the path of the iso in the section that says if=. Then press enter and wait. Then when the command is finished, let's move on to the next step.

## Setup

* Then wait and boot the system with USB. You can see how to do it web.

* Then perform the installation instructions and it's done! You have now changed the distro.
