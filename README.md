fmalpartida New LiquidCrystal Library
=====================================
Adapted for Spark Core by Paul Kourany, July 2014

```
Created by Francisco Malpartida on 20/08/11.
Copyright 2011 - Under creative commons license 3.0:
        Attribution-ShareAlike CC BY-SA

This software is furnished "as is", without technical support, and with no 
warranty, express or implied, as to its usefulness for any purpose.

@brief 
This is a basic implementation of the HD44780 library of the
Arduino SDK. This library is a refactored version of the one supplied
in the Arduino SDK in such a way that it simplifies its extension
to support other mechanism to communicate to LCDs such as I2C, Serial, SR, ...
The original library has been reworked in such a way that this will be
the base class implementing all generic methods to command an LCD based
on the Hitachi HD44780 and compatible chipsets.

This base class is a pure abstract class and needs to be extended. As reference,
it has been extended to drive 4 and 8 bit mode control, LCDs and I2C extension
backpacks such as the I2CLCDextraIO using the PCF8574* I2C IO Expander ASIC.


@version API 1.1.0

2012.03.29 bperrybap - changed comparision to use LCD_5x8DOTS rather than 0
@author F. Malpartida - fmalpartida@gmail.com
```

