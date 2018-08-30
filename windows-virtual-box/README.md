# Windows Virtual Machine on OSX

## Install Windows virtual machines on VirtualBox

#### Need to run a Windows-only program on your Mac?&nbsp; Need to test browser compatibillity for MS Edge or IE11?&nbsp; Look no further!

#

## Download

[Download VirtualBox](https://www.virtualbox.org/wiki/Downloads)

[Microsoft Virtual Machines](https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/)

- Windows 10 (recommended) 
    - download/install programs
    - test Edge & IE11
- Windows 7
    - test IE11 (and the other dinosaurs)
    - faster startup

#

## Installation

#### If installation fails on High Sierra:

1. reboot
2. during reboot, hold ⌘-R
3. click Utilities -> Terminal
4. enter: &nbsp; `csrutil disable`
5. close Terminal, reboot
6. remove remnants of failed install and reattempt
7. after install, repeat steps 1-3 and enter: &nbsp; `csrutil enable`

#

## Setup

#### Coming soon.

#

## Renew 90 day activation

#### Windows authorizes use of the VM for 90 days.  To extend your registration and avoid having to start from scratch every three months, open the Windows command prompt as an administrator and follow these steps:

- enter: &nbsp; `slmgr -rearm`
- reboot VM
- enter: &nbsp; `slmgr -ato`