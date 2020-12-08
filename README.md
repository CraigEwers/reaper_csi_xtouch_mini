# Reaper CSI - X-Touch Mini files

Works with Reaper CSI v1.0 (Dec 4 2020)

These files configure the excellent Reaper CSI add-in to utilise a Behringer X-Touch Mini controller for basic 8 channel live recording/mixing use.

The X-Touch Mini must be configured in "standard" mode (not MCU mode) for this to work properly, I previously have had a poor experience trying to use the MCU mode so found it better to work from the standard baseline.

## General Operation

### Layer A

* Rotaries operate as volume controls (currently no action for rotary push)
* First row of buttons toggle record/arm
* Second row of buttons mostly mirror the icons beside the button (from left to right):
  * Bank left (by 8 channels/tracks)
  * Bank right (by 8 channels/tracks)
  * Rewind to previous marker/start of project
  * Fast Forward to next marker/end of project
  * toggle loop
  * Stop
  * Play/Pause
  * Record
* Fader control is Master Fader

### Layer B

* Rotaries operate as pan/pan width controls (toggled by rotatry push)
* First row of buttons toggle mute
* Second row of buttons toggle solo
* Fader control is Master Fader

## X-Touch Mini Configuration (using X-Touch Editor)

* Firmware Version: 1.08
* Editor Version: 1.21
* Device ID: ID 1
* Global Channel: CH 1

From factory default, change the following:

### Layer A

* Set Encoder "LED Ring" to **Fan** for all 8 channels
  
### Layer B

* Set Encoder "LED Ring" to **Pan** for all 8 channels

## Known Issues

1 Banking and changing layers - rotaries on the inactive layer are not updated, causing inaccurate display when changing layers

2 Button lights no longer seem to stay lit to indicate status
