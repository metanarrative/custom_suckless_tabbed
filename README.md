# custom_suckless_tabbed
Customized tabbed from suckless project (suckless.org). Contains tab rename functionality + changed keybindings.
Renaming functionality was retrieved from this repo: https://github.com/gch1p/tabbed-renametab-mod.git , then added into fresh tabbed version.
Code for tab renaming is commented as '//rename func patch' in case you wish to get solely it for your custom build.
Be aware that you need dmenu installed in order renaming patch to work.

Default tabbed README:

tabbed - generic tabbed interface
=================================
tabbed is a simple tabbed X window container.

Requirements
------------
In order to build tabbed you need the Xlib header files.

Installation
------------
Edit config.mk to match your local setup (tabbed is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install tabbed
(if necessary as root):

    make clean install

Running tabbed
--------------
See the man page for details.
