# esp32-nature-watch

An ESP32 nature camera.

**This is very much a Work-In-Progress and so these notes are more to help me with development**

## Design Notes

 * Low-power, so wake up from a PIR sensor kick, take a photo and go to sleep
 * Options to...
   * Save to micro-SD card
   * Publish to the Internet.  Post to [Pleroma](https://pleroma.social/)?

## Installation Notes

The ESP32-CAM module I have is an AiThinker ESP32-CAM with an OV2640 camera.  Pin 0 needs to be pulled to ground to enter programming mode.

## Useful Links

 * https://randomnerdtutorials.com/esp32-cam-video-streaming-face-recognition-arduino-ide/
