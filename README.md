# Reaper CSI - X-Touch Mini files

Works with Reaper CSI v1.0 (Dec 10 2020)

These files configure the excellent Reaper CSI add-in to utilise a Behringer X-Touch Mini controller for basic 8 channel live recording/mixing use.

The X-Touch Mini must be configured in MC mode (not Standard mode) for this to work properly, I have recently found this gives better support for the rotaries as well as the lights on the buttons so for CSI v1.0 I have completely restarted from scratch.

## General Operation

### Normal - No Modifiers

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
* Button A is "Shift"
* Button B is "Option"

### With Shift held/latched

* Rotaries operate as Pan/Pan Width controls (toggled by rotatry push)
* First row of buttons toggle mute

### With Option held/latched

* First row of buttons toggle solo

## X-Touch Mini Configuration (using X-Touch Editor)

* Firmware Version: 1.08
* Editor Version: 1.21
* Mode: MC
* Device ID: ID 1
* Global Channel: CH 1
