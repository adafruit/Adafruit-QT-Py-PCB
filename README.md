## Adafruit QT Py PCB

<a href="http://www.adafruit.com/products/4600"><img src="assets/4600.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit QT Py.

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4600

### Description

What a cutie pie! Or is it... a QT Py? This diminutive dev board comes with our favorite lil chip, the SAMD21 (as made famous in our GEMMA M0 and Trinket M0 boards).

This time it comes with our favorite connector - the STEMMA QT, a chainable I2C port that can be used with any of our STEMMA QT sensors and accessories.

OLEDs! Inertial Measurment Units! Sensors a-plenty. All plug-and-play thanks to the innovative chainable design: SparkFun Qwiic-compatible STEMMA QT connectors for the I2C bus so you don't even need to solder! Just plug in a compatible cable and attach it to your MCU of choice, and you’re ready to load up some software and measure some light.

Use any SparkFun Qwiic boards! Seeed Grove I2C boards will also work with this adapter cable.

Pinout and shape is Seeed Xiao compatible, with castellated pads so you can solder it flat to a PCB. In addition to the QT connector, we also added an RGB NeoPixel (with controllable power pin to allow for ultra-low-power usage), and a reset button (great for restarting your program, or entering the bootloader)

Runs Arduino like a dream, and can be used for basic CircuitPython projects. For more advanced usage like datalogging or file storage, solder an SOIC SPI flash chip onto the bottom pads,

    Same size, form-factor, and pin-out as Seeed Xiao
    ATSAMD21E18 32-bit Cortex M0+ - 48 MHz 32 bit processor with 256KB Flash and 32 KB RAM
    Native USB supported by every OS - can be used in Arduino or CircuitPython as USB serial console, MIDI, Keyboard/Mouse HID, even a little disk drive for storing Python scripts.
    Can be used with Arduino IDE or CircuitPython
    Built in RGB NeoPixel LED
    11 GPIO pins:
        True analog output on one I/O pin - can be used to play 10-bit quality audio clips in Arduino (CircuitPython does not have storage for audio clips)
        9 x 12-bit analog inputs (SDA/SCL do not have analog inputs)
        1 x Optional AREF on A1
        9 x PWM outputs (A0 is analog out, A1 is not PWM capable)
        Hardware I2C port with STEMMA QT plug-n-play connector
        Hardware UART
        Hardware SPI
        Hardware I2S
        6 x Capacitive Touch with no additional components required
    3.3V regulator with 600mA peak output
    Optional SOIC-8 SPI Flash chip on bottom
    Reset switch for starting your project code over or entering bootloader mode
    USB Type C connector
    Really really small

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution.
See license.txt for additional details.
