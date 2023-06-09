# pico-oled-demo
Practicing with the rp2040 pi pico, and a SSD1306 for general micropython and PIO stuff.

## [3d_wireframe_animation.py](./oled-demo-ssd1306/3d_wireframe_animation.py)

<p align="center">
  <img src="img/spinning_cube.gif" alt="image" style="width: auto; height: auto;">
</p>

# Try it NOW
[Wokwi awesome web-hosted Pico2040 simulator🤓](https://wokwi.com/projects/362799539846585345)


# Pico OLED Demo(s)

This project is a container of demos using the RP2040 Pi Pico and a SSD1306 OLED display with Micropython. The demo code provides an example of how to initialize the I2C interface, connect to the OLED display, and render some interesting framebuff demos.

## [3d_wireframe_1.py](./oled-demo-ssd1306/3d_wireframe_1.py)
<p align="center">
  <img src="img/3d_wireframe_1.png" alt="image" style="width: 30%; height: auto;">
</p>

## [scrolling_words.py](./oled-demo-ssd1306/scrolling_words.py)
<p align="center">
  <img src="img/scrolling_words.gif" alt="image" style="width: 30%; height: auto;">
</p>

## [many_squares.py](./oled-demo-ssd1306/many_squares.py)
<p align="center">
  <img src="img/many_squares.jpg" alt="image" style="width: 30%; height: auto;">
</p>



## Getting Started

To use this demo code, you will need a RP2040 Pi Pico board and a SSD1306 OLED display. You will also need to have Micropython installed on your board.

### Wiring

Connect the SSD1306 OLED display to the RP2040 Pi Pico board as follows:

- OLED VCC to Pico 3V3 pin
- OLED GND to Pico GND pin
- OLED SCL to Pico GP1 pin
- OLED SDA to Pico GP0 pin

### Installing Micropython

If you haven't already, you will need to install Micropython on your RP2040 Pi Pico board. Instructions for doing so can be found in the [official Micropython documentation](https://micropython.org/download/rp2-pico/).

### Running the Demo
1. Clone the repo
2. `cd pico-oled-demo`
3. `rshell -f rshell.script`
4. *CTRL*+*D*: to reset the pico and start the program!
5. *CTRL*+*C*: to stop and *CTRL*+*X* to exit.

This will copy a demo to the pico, then connect you to the REPL

### Running the Demo Manually
1. Copy the demo code to a file named `main.py` on your RP2040 Pi Pico board.
2. Connect your RP2040 Pi Pico board to your computer via USB.
3. Use a terminal program to connect to the board's serial console at a baud rate of 115200. [I'm a big fan of rshell](https://github.com/dhylands/rshell)
4. Reset the board by pressing the RESET button.

## TODO
5. The OLED should now be doing its thing, with the RESET button having been hijacked to cycle through demos!


## Acknowledgments

This project is inspired by the excellent [Adafruit_SSD1306 library](https://github.com/adafruit/Adafruit_SSD1306) and the [official Micropython documentation](https://docs.micropython.org/en/latest/). Special thanks to the Micropython and Pi Pico communities for their support and contributions.
