# -PS4-Controller-ESP32-project

This project is an interface designed to connect a modern PlayStation 4 (PS4) controller to old gaming consoles and vintage computers that use different types of physical control ports.
Its main objective is to bridge the technological gap between modern Bluetooth controllers and legacy systems that were originally designed for simple wired digital inputs. By converting PS4 controller commands into hardware signals that are compatible with classic devices, this interface allows players to use modern, ergonomic controllers without modifying or altering the original equipment.

To handle wireless communication and controller input decoding, the project uses the Bluepad32 library, developed by Retro.Moe. This library enables high-performance Bluetooth controller support on embedded hardware, simplifying the integration between modern gamepads and custom electronic interfaces.

The software reads all relevant PS4 controller inputs, including buttons, D-Pad, analog sticks, shoulder triggers, and special function keys, then translates them into the appropriate electrical outputs required by the target system. This makes it possible to control multiple retro platforms using only one modern controller interface.

In summary, this project combines modern Bluetooth technology, the Bluepad32 library, and classic controller communication standards into one unified interface that brings retro gaming back to life with modern comfort and reliability.
