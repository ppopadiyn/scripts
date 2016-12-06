# Scripts
Contains various automation scripts

### /beaglebone/InitOverUsb.sh
Set up the following services on beaglebone:

1. Initialize internet over usb.
2. Sync the current datetime by using ntpdate.
 1. If `ntpdate` cannot be found, `apt-get update` and `apt-get install ntpdate`

[Reference](http://ofitselfso.com/BeagleNotes/HowToConnectBeagleboneBlackToTheInternetViaUSB.php)
