# Hardware_IO_Interfaces

This repository defines a package gathering software elements allowing to manage input and output
pin of an hardware device.

The package is designed following
[this meta-model](https://github.com/HomeMadeBots/Embedded_Software_Meta_Model) and implemented
according to [these C language
patterns](https://github.com/HomeMadeBots/C-language-patterns-for-Embedded-Software-Meta-Model).

## Content

The Hardware_IO_Interfaces package gathers :
* Data_Types :
  * T_Voltage_5
  * E_IO_Level
* Client_Server_Interface :
  * Analogic_Input_5
  * Discrete_Input
  * Discrete_Output
  
## Overview

![Overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/Hardware_IO_Interfaces/master/doc/overview.puml)

## Dependencies

None.

## Use

### With the Arduino IDE

This repository shall be clone within the _librairies_ folder of the _Arduino sketchbook folder_.