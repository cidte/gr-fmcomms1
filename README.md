# gr-fmcomms1
This is a source and sink blocks to work with the AD-FMCOMMS1-EBZ board in GNU Radio.

## Getting started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

First, you have to do a git clone on this repository:

'''
git clone https://github.com/cidte/gr-fmcomms1.git
'''

### Prerequisites
You need to install some dependencies before you can use the blocks, these are the most important:
'''
libiio (https://wiki.analog.com/resources/tools-software/linux-software/libiio)
libad9361-iio (https://github.com/analogdevicesinc/libad9361-iio)
GNU Radio (https://www.gnuradio.org)
gr-iio (https://github.com/analogdevicesinc/gr-iio)
'''

### Building and installing
To build the blocks into GNU Radio you need to do a build dir and change directory into it

'''
$mkdir build

$cd build
'''

Then you build the project into this directory:

'''
$cmake ../

$make
'''

Then you can install the project:

'''
$make install
'''

It is recommended to reconfigure the dynamic linker with:

'''
$ldconfig
'''

NOTE: You may need sudo permissions to install the project and reconfigure the linker.


