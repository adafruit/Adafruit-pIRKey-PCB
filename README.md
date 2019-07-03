## Adafruit pIRKey PCB

<a href="http://www.adafruit.com/products/3364"><img src="assets/image.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit pIRKey. Format is EagleCAD schematic and board layout

For more details, check out the product pages at
* https://www.adafruit.com/product/3364

### Description

The pIRkey adds an IR remote receiver to any computer, laptop, tablet...any computer or device with a USB port that can use a keyboard. This little board slides into any USB A port, and shows up as an every-day USB keyboard. The onboard ATSAMD21 microcontroller listens for IR remote signals and converts them to keypresses, mouse movements, or even USB serial output.

**Coming soon! We want to reprogram our stock with the newest CircuitPython version before shipping these out.**

Infrared is our favorite wireless protocol - no antennas, certifications, pairings, passwords, or special tools required. Works everywhere in the world and very intuitive - everyone's got an IR remote in their home!  Our original IRkey was a small USB-pluggable microcontroller board with an IR receiver, an Attiny85 microcontroller and indicator LED. When certain remote control commands were received, the IRkey would send corresponding keyboard presses. It was great, but was not easy to customize - you had to use the remote we sold it with.

The pIRkey is an improvement on our original IRkey product, by adding a p for python. Now that we have CircuitPython available for the tiny ATSAMD21E processor, we swapped it for the ATtiny85, giving a huge boost in power and a working Python interpreter on board as well. This means its super easy to reprogram, customize or adapt it to whatever Infrared-reading needs you may have.

When you plug it in, the pIRkey shows up as a triple device: USB disk drive to store code, USB serial for debugging and Python interactive command line, and USB keyboard/mouse that can transmit keypresses or mouse movements.

By default we ship with some very simple example code to read NEC remotes but you can use any remote that has about 38KHz output frequency which is the vast majority of remote controls. Here's some ideas: you could use pIRkey to remotely start/stop a program, shut down a computer, control a smart phone or tablet mounted far away, make adaptive controls, etc.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
