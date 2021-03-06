Gadgetbridge
============

Gadgetbridge is an Android (4.4+) Application which will allow you to use your
Pebble or Mi Band without the vendor's closed source application and without the
need to create an account and transmit any of your data to the vendor's servers.

## Features (Pebble)

* Incoming calls notification and display (caller, phone number)
* Outgoing call display
* Reject/hangup calls
* SMS notification (sender, body)
* K-9 Mail notification support (sender, subject, preview)
* Support for generic notificaions (above filtered out)
* Apollo playback info (artist, album, track)
* Music control: play/pause, next track, previous track, volume up, volume down
* List and remove installed apps/watchfaces
* Install .pbw files
* Install firmware from .pbz files (EXPERIMENTAL)

## How to use (Pebble)

1. Pair your Pebble through Gadgetbridge's Discovery Activity or the Android Bluetooth Settings
2. Start Gadgetbridge, tap on the device you want to connect to
3. To test, choose "Debug" from the menu and play around

## Features (Mi Band)

* Mi Band notifications (LEDs + vibration) for 
    * Discovery and pairing
    * Incoming calls
    * SMS received
    * K-9 mails received
    * Generic Android notifications
* Synchronize the time to the Mi Band
* Display firmware version and battery state

## How to use (Mi Band)

* When starting Gadgetbridge and no device is visible, it will automatically
  attempt to discover and pair your Mi Band. Alternatively you can invoke this
  manually via the menu button. It will ask you for some personal info that appears
  to be needed for proper steps calculation on the band. If you do not provide these,
  some hardcoded default "dummy" values will be used instead. 

  When your Mi Band starts to vibrate and blink with all three LEDs during the pairing process,
  tap it quickly a few times in a row to confirm the pairing with the band.

1. Configure other notifications as desired
2. Go back to the "Gadgetbridge" Activity
3. Tap the "MI" item to connect if you're not connected yet.
4. To test, chose "Debug" from the menu and play around

Known Issues:

* Android 4.4+ only, we can only change this by not handling generic
  notifications or by using AccessibiltyService. Don't know if it is worth the
  hassle.

* The initial connection to a Mi Band sometimes takes a little patience. Try to connect a few times, wait, 
  and try connecting again. This only happens until you have "bonded" with the Mi Band, i.e. until it 
  knows your MAC address. This behavior may also only occur with older firmware versions.

## Contribute

Contributions are welcome, be it feedback, bugreports, documentation, translation, research or code. Feel free to work
on any of the open [issues](https://github.com/Freeyourgadget/Gadgetbridge/issues?q=is%3Aopen+is%3Aissue);
just leave a comment that you're working on one to avoid duplicated work.

Translations can be contributed via https://www.transifex.com/projects/p/gadgetbridge/resource/strings/ or
manually.

## Download

[![Gadgetbridge on F-Droid](/Get_it_on_F-Droid.svg.png?raw=true "Download from F-Droid")](https://f-droid.org/repository/browse/?fdid=nodomain.freeyourgadget.gadgetbridge)

