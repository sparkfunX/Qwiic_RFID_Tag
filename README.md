# SparkX ST25DV64KC Dynamic NFC/RFID Tag

<p align="center">
    <a href="https://github.com/sparkfunX/Qwiic_RFID_Tag/blob/master/LICENSE" alt="License">
        <img src="https://img.shields.io/badge/license-MIT-blue.svg" /></a>
    <a href="https://twitter.com/intent/follow?screen_name=sparkfun">
                    <img src="https://img.shields.io/twitter/follow/sparkfun.svg?style=social&logo=twitter"
                          alt="follow on Twitter"></a>
</p>

<table class="table table-hover table-striped table-bordered">
    <tr align="center">
     <td><a href="https://www.sparkfun.com/products/19035"><img src="https://cdn.sparkfun.com/assets/parts/1/8/6/3/6/19035-Qwiic_RFID_Tag-01.jpg"></a></td>
    </tr>
    <tr align="center">
        <td><a href="https://www.sparkfun.com/products/19035">SparkFun Qwiic Dynamic RFID Tag - ST25DV64KC (SPX-19035)</a></td>
    </tr>
</table>

The STMicroelectronics ST25DV _**dynamic**_ Near Frequency Communication / Radio Frequency Identification tag ICs are awesome! The ST25DV64KC offers 64-kBit (8-kBytes) of EEPROM memory which can be accessed over both I2C and RF (NFC)! It's a state-of-the-art tag which conforms to ISO/IEC 15693 or NFC Forum Type 5 recommendations. You can read and write the tag's memory using NFC even while the tag is powered down or disconnected!

The EEPROM memory can be divided into four areas, each of which can have different levels of protection applied. Want to store your data so everyone has read and write access over both I2C and RF? You can do that.
In fact, that's the default! Want to store your data in an area which can only be read if you know the password, and cannot be written to (via RF)? You can do that too!

Our [Arduino Library](https://github.com/sparkfun/SparkFun_ST25DV64KC_Arduino_Library) provides all of the methods you need to read and write the user memory, control the read and write permissions, alter the area sizes and apply password control. Not only that! We've included extra methods which will let you read and write **NDEF (NFC Forum Data Exchange Format) URI, WiFi and Text records** which your smart phone can understand!

Do you want your project to be able to log up to 8-kBytes of data (via I2C) and then be able to read it using your smart phone - even if your project is powered off? Our library lets you do that!

Do you want to be able to write WiFi credentials (SSID and Password) into tag memory using your smart phone and then to be able to read them over I2C so your Arduino board can join the network? With our library you can do that too!

Do you want to be able to manufacture and test your product and then program it with keys or other credentials just before you ship? We've got you covered.

Are you developing equipment or appliances for the home? Would you like to store diagnostic information so that the repair engineer can access it using their smart phone? Our library lets you do that! Would you like the customer to be able to read the diagnostics with _their_ smart phone and then email them to you? Our library will let you do that too! (Apart from the email bit - obvs.. You will need to add that bit yourself.)

Are you designing a poster for your project? Do you want to be able to program your tag using Arduino and then stick it to your poster so people can interact with it? Hey, we've got you covered there too!

## Arduino Library Documentation

A full library use overview, API reference guide and key example walk-throughs are available on GitHub Pages - [sparkfun.github.io/SparkFun_ST25DV64KC_Arduino_Library](https://sparkfun.github.io/SparkFun_ST25DV64KC_Arduino_Library/)
