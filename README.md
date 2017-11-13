# Overview of MRAA and UPM Library

## What is the MRAA Library?

Libmraa is a C/C++ library with bindings to Java, Python and JavaScript to interface with the IO on a variety of IoT boards. Use of libmraa abstracts your specific hardware and uses board detection at runtime to create portable code that will work across many supported platforms.

The intent is to make it easier for developers and sensor manufacturers to map their sensors & actuators on top of supported hardware and to allow control of low level communication protocol by high level languages & constructs.

## Architecture of I/O using MRRA and UPM
MRRA and UPM are application level libraries that are used in IoT applications to communicate with sensors and actuators.

Here's is a diagram showing the relations between the hardware and the IoT application.

The MRAA library provides abstractions for the following I/O types:
 * [General Purpose Input and Output (GPIO)](https://en.wikipedia.org/wiki/General-purpose_input/output)
 * Analog I/O - uses an [Analog to Digital Converter](https://en.wikipedia.org/wiki/Analog-to-digital_converter) to convert to and Arduino standard 10 bit value (0 to 1023).
 * [Pulse Width Modulation (PWM)](https://en.wikipedia.org/wiki/Pulse-width_modulation)
 * [Inter-integrate Circuit (I2C)](https://en.wikipedia.org/wiki/I%C2%B2C)
 * [Serial Peripheral Interface Bus (SPI)](https://en.wikipedia.org/wiki/Serial_Peripheral_Interface_Bus)
 * [Universal asynchronous receiver-transmitter (UART)](https://en.wikipedia.org/wiki/Universal_asynchronous_receiver-transmitter)

![Architecture](./images/arch.png)

Together these interfaces provide an I/O layer that can support many devices that sensor and take actions in a physical environment.

Two IDEs that have support for the MRAA and UPM libraries are [Arduino Create](https://create.rduino.cc) and [Intel System Studio](). However, since MRAA and UPM include bindings for Java, Python, JavaScript, C++ and C, you can, of course, use an IDE or editor of your choice.

## Open the MRAA API Documentation
We will now open the API Documentation page for the MRAA C++ library. Please, keep this page open as you will refer to it during the rest of the lab exercises.

:arrow_forward: **Open the [MRAA API Documentation page for C++](https://iotdk.intel.com/docs/master/mraa/)**

If you are interested you can also open the API Reference pages for other language bindings.
* [MRAA API Documentation for Java](https://iotdk.intel.com/docs/master/mraa/java/)
* [MRAA API Documentation for Python](https://iotdk.intel.com/docs/master/mraa/python/)
* [MRAA API Documentation for JavaScript](https://iotdk.intel.com/docs/master/mraa/node/)

## What is the UPM Library?
