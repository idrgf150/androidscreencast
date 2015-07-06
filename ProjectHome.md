Desktop app to control an android device remotely using mouse and keyboard.
Should work on Windows/Linux/MacOS with any android device.

I've created a google groups [HERE](http://groups.google.com/group/androidscreencast) for support, no direct help request please.

# Installation #

  1. Install the android sdk ([download here](http://developer.android.com/sdk/index.html))
  1. Connect your device through USB cable and ensure it's detected with "adb devices"
  1. Make sure you have Java Runtime Environnement 5 or later installed
  1. Click [HERE](http://androidscreencast.googlecode.com/svn/trunk/AndroidScreencast/dist/androidscreencast.jnlp). You can launch it by typing "javaws <jnlp file>" from a command line.

If mouse/keyboard control doesn't work, open a command line and type :
  * adb shell
  * su
  * chmod 777 /data/dalvik-cache
  * cd /data/dalvik-cache
  * chmod 777 ./

# Features #

  * Mouse and keyboard control FOR ROOTED DEVICES ONLY
  * Landscape mode (right click)
  * Video recording
  * Basic file browser

# Current limitations #

  * Slow refresh rate (about 4-5 fps)
  * Not all keycode are mapped. See [KeyMapping](KeyMapping.md)

# Todo #

  * Automatic screen rotation based on the device current state.
  * Improve speed
  * Audio redirection

# How can i help ? #

  * Donate using this button : [![](http://www.paypal.com/en_US/i/btn/x-click-but04.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=YGPKQZT563WZU&lc=US&item_name=Android%20Screencast&item_number=androidscreencast&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donate_LG%2egif%3aNonHosted) (Thank Daniel and Tyler !)
  * Report issues, submit patch, ...


![http://androidscreencast.googlecode.com/files/screenshot.jpg](http://androidscreencast.googlecode.com/files/screenshot.jpg)