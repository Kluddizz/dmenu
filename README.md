# dmenu - dynamic menu
dmenu is an efficient dynamic menu for X.

## Changes I made
* Added `padding` option in configuration file to change the padding of the top bar.

## Requirements
In order to build dmenu you need the Xlib header files.


## Installation
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install


## Running dmenu
See the man page for details.
