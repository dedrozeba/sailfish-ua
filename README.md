# sailfish-ua
To install the keyboard you should enable Developer mode in your phone's settings.
Proceed to Developer tools and allow it. Also enable Remote connection.
Copy uk.conf and uk.qml files to Jolla. Then ssh to your device and type 'devel-su'.
Input the same password that you used to login to the device.
Place the files in /usr/share/maliit/plugins/com/jolla/layouts.
Make sure the permissions are the same as the other files already present in this directory.
As root run 'systemctl --user restart maliit-server.service'.
After that the Ukrainian keyboard should appear in the Keyboards list in Text input section of Settings.
