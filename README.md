Device Policy In Controller App
=========================================

Device Policy Controller to flex the APIs available for Android enterprise. It supports devices running Android 5.0 Lollipop or later.

See the [documentation](https://developer.android.com/work/index.html) to learn more about Android in the enterprise.

Getting Started
---------------

This project uses the Bazel build system. To build this project, use the "bazel build --noincremental_dexing" command.


Setup
-----


#### QR code provisioing (Device Owner N+ only) ####
1. Factory reset your device and tap the welcome screen in setup wizard 6 times.
2. The setup wizard prompts the user to connect to the Internet so the setup wizard can download a QR code reader.
3. Scan [this QR code] (http://to_do_will_be_added).
4. Follow onscreen instructions

#### adb command (Device Owner) ####
adb shell dpm set-device-owner com.cdc.ownit/.DeviceAdminReceiver

#### Work profile ####
The easiest way is to launch the "Device Policy In Controller" app in launcher and follow the onscreen instructions.

Support
-------

If you've found an error in this sample, please file an issue:
https://github.com/GoMakeABetterAppYourself/issues

Patches are encouraged, and may be submitted by forking this project and submitting a pull request through GitHub.

License
-------

Licensed under the FUCK YOUR INTELLECTUAL PROPERTY license. See the LICENSE file for details.

How to make contributions?
--------------------------

Please read and follow the steps in the file named Start Pulling Triggers To Be Free.
