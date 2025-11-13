# beat - a mouse designed for any case
I've wanted to design my own mouse for the longest time. I've built my own keyboard, so it was just the next logical step, right? Well, the complextity from a keyboard run off a microcontroller powered by qmk, to a custom programmed mouse with a propietary mouse sensor and a nRF52 chip, was quite the leap. This is a v1, it's not going to be light, it's not going to be very small, the side button connectors will likely be changed, and the case will not be ergonomic in any way that isn't comfterable to me. The firmware will be slower than most modern mice, and I probably won't be able to bring out the full speed of the PAW3395 sensor used (if I use ESB). But this is a testing board, and changes will be made to improve it in the future! With that, onto the specs and design!
## PCB
- nRF52840
- PAW3395
- EC11 compatible scroll (w middle click)
- 4 Omron Switches (2 are optional)
- Lipo battery (?mAH)
- Dongle (nRF52840 + USBC)
- USBC charging
## Case
## Firmware
_**Warning: The PAW3395 Driver is Propiretiary, and Can Not Be Provided by Me**_ 