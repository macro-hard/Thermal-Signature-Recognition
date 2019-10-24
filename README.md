# Invasive Species Mapper (ISM)

According to the [U.S. Forest Service][1] "invasive species have contributed to the decline of 42% of U.S. endangered and threatened species, and for 18% of U.S. endangered or threatened species, invasives are the main cause of their decline."

So, what is an invasive species? An invasive species is one that is foreign to the local ecosystem and has the potential to cause economic or environmental damage.

Our mission is to research the feasibility of using thermal imaging to recognize the heat signatures of these invasive species. We want to be able to use drones mounted with thermal cameras to recognize and plot the locations of these plants, specifically targeting densely populated areas so that efforts can be focused to more efficiently control the invasion. The drone will operate on designated routes searching for invasive species. When the thermal camera registers that it has spotted the invasive species it will then plot the location and name of the species that it found.

The goal of this project is twofold: 
* To make the process of locating and identifying the invasive species an easily implemented passive process, allowing the customer to spend more time on other potentially more important tasks, increasing efficiency.
  
* To make the end product affordable to the point that a ?common/smalltime? farmer is able to afford a decent number of the drones without being a financial burden. 

##  Getting Started

The software used to flash the Arduino Chip is the Arduino IDE which can be downloaded from [here][2].


Within the IDE there were multiple libraries that need to be installed in order to use the camera and display.
They are found in the Arduino IDE under Tools > Manage Libraries.
For the camera search for Adafruit GFX Library.
For the display search for Adafruit ILI9341.


For the Arduino 32u4 board there is an additional download needed.
In the Arduino IDE under Tools > Boards > Board Manager search for Adafruit AVR Boards.

## Built With

* Adafruit AMG8833 IR Thermal Camera FeatherWing

![Adafruit AMG8833 IR Thermal Camera FeatherWing Image](https://raw.githubusercontent.com/macro-hard/Thermal-Signature-Recognition/assets/Hardware%201.JPG)

* TFT FeatherWing - 2.4" 320x240 Touchscreen For All Feathers

![TFT FeatherWing - 2.4" 320x240 Touchscreen For All Feathers Image](https://raw.githubusercontent.com/macro-hard/Thermal-Signature-Recognition/assets/Testing1.jpg)
* Adafruit Feather 32u4 Adalogger

## Authors

* John Geddeis - MSSA
  
* Justin Hughes - MSSA
* Jordan Ketterling - MSSA


See also the list of contributors who participated in this project.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

[1]: https://www.fs.fed.us/wildflowers/invasives/index.shtml
[2]: https://www.arduino.cc/en/main/software
