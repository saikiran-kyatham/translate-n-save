# translate-n-save

# Setting up the development environment
Development OS: Windows
Target OS: Android

# Installing dependencies
We recommend installing Node and Python2 via Chocolatey, a popular package manager for Windows.
choco install -y nodejs.install python2 jdk8

To install chocolately on windows follow link:
https://chocolatey.org/courses/installation/installing?method=installing-chocolatey?quiz=true

If you have already installed Node on your system, make sure it is Node 8.3 or newer.
If you already have a JDK on your system, make sure it is version 8 or newer.

# Android development environment

# 1. Install Android Studio
Choose a "Custom" setup when prompted to select an installation type. Make sure the boxes next to all of the following are checked:
1 Android SDK
2 Android SDK Platform
3 Performance (Intel ® HAXM) (See here for AMD)
4 Android Virtual Device

# 2. Install the Android SDK
The SDK Manager can be accessed from the "Welcome to Android Studio" screen. Click on "Configure", then select "SDK Manager".
OR
The SDK Manager can also be found within the Android Studio "Preferences" dialog,
under Appearance & Behavior → System Settings →         Android SDK.

Select the "SDK Platforms" tab from within the SDK Manager, then check the box next to "Show Package Details" in the bottom right #     corner. Look for and expand the Android 9 (Pie) entry, then make sure the following items are checked:
1 Android SDK Platform 28
2 Intel x86 Atom_64 System Image or Google APIs Intel x86 Atom System Image

Next, select the "SDK Tools" tab and check the box next to "Show Package Details" here as well. Look for and expand the "Android SDK # Build-Tools" entry, then make sure that 28.0.3 is selected.

Finally, click "Apply" to download and install the Android SDK and related build tools.

# 3. Configure the ANDROID_HOME environment variable
# 4. Add platform-tools to Path

you can check at the official documentation of react-native https://reactnative.dev/docs/environment-setup