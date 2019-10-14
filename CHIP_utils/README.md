# About

This folder contains tools for controlling rc remote controlled power sockets
with [C.H.I.P](getchip.com) devices.


## Usage

After that you can compile the example program *send* by executing *make*. 

## Note
The 'send' and 'sendcode' code is as yet untested.  It _should_ work, but it is still being tested thoroughly.  It's provided to allow you to start playing with it now.


## Pusky Notes to build for CHIP

git clone https://github.com/WiringPi/WiringPi.git  and build on CHIP
git clone git@github.com:puskyer/CHIP_IO.git and symlink to 433Utils/rc-switch/CHIP_IO
exicute only first time 433utils/CHIP_utils/setup_patch.sh
