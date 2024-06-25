# T-Encoder-Pro
An example project for LILYGO's [T-Encoder-Pro](https://www.lilygo.cc/products/t-encoder-plus) using the [PlatformIO](https://platformio.org) IDE, [Arduino](https://www.arduino.cc/) framework, and [LVGL](https://lvgl.io/) graphics library.

**Note 1:** The code base at this state is adapted from nikthefix's [Lilygo_Support_T_Encoder_Pro_Smart_Watch](https://github.com/nikthefix/Lilygo_Support_T_Encoder_Pro_Smart_Watch) example, the plan is to provide a cleaner starting point just like my [T-Display-S3](https://github.com/KamranAghlami/T-Display-S3) project, hopefully soon.

**Note 2:** I've noticed some flash corruptions when uploading, if this happens you need to enter boot mode before uploading and restart the board afterward. The boot button is connected to the encoder's click button, so you should press the display and power cycle the device while holding it, either by pressing the reset or re-plugging the USB cable.
