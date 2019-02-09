# BMS-Board
A battery management system with active cell balancing

![BMS-Board v1.0.1](https://user-images.githubusercontent.com/30117490/52515127-331ebb00-2c18-11e9-955f-3e2340149870.png "BMS-Board v1.0.1")

## PCB

The prototype is realized with a 4-layer printed circuit board (200 mm x 85 mm):

![BMS-Board PCB v1.0.1](https://user-images.githubusercontent.com/30117490/52515166-7711c000-2c18-11e9-9149-2ad6bf0acc8f.png "BMS-Board PCB v1.0.1")

## Download

* [**BMS-Board v1.0.1**](https://github.com/MuellerDominik/BMS-Board/releases/download/v1.0.1/BMS-Board_v1_0_1.zip "BMS-Board v1.0.1") - Latest release
* [BMS-Board v1.0.0](https://github.com/MuellerDominik/BMS-Board/releases/download/v1.0.0/BMS-Board_v1_0_0.zip "BMS-Board v1.0.0") - Manufactured prototype

## Changelog

* **v1.0.1**
  * Fixed exchanged bias current resistors (R18, R19).
  * Added pull-up resistors (R32 - R38) to the GPIO pins 3 - 5 (SPI) and 6 - 9 (CS).
  * Changed the value of the series resistor (R23) of the PT1000 to 1 kOhm.
  * Changed the value of the parallel ceramic capacitor (C24) of the PT1000 to 100 nF (no longer populated).
  * Repositioned the PT1000 (R25) to reduce heating from the board (thermal coupling has also been reduced).
* **v1.0.0**
  * Initial release

## Authors

* Nico Canzani ([@nicoca20](https://github.com/nicoca20 "Nico Canzani"))
* Dominik Müller ([@MuellerDominik](https://github.com/MuellerDominik "Dominik Müller"))

## License

Copyright &copy; 2018 pro3E - Team4

This project is licensed under the MIT License - see the [LICENSE](LICENSE "LICENSE") file for details
