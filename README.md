Luci
====

project/luci from http://git.openwrt.org/

Making changes to OpenWrt VirtualBox
====

Run the "sendImportantStuffToOpenWrtVM" script the first time you import the OpenWrtVM into virtualbox to replace the corrupt uci.lua file and create the wireless config file.

Run the "sendAppToOpenWrtVM" script from the Luci directory by typing "sh sendAppToOpenWrtVM" from the command line each time you change the sys.lua file.
