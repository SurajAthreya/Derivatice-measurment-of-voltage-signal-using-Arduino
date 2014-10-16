Derivatice-measurment-of-voltage-signal-using-Arduino
=====================================================

The voltage signal is being read using the Arduino and its derivative values with respect to time are computed and tabulated.
I need to display the same on a TFT-LCD display and store the values in memory.

The millis() function is used to keep track of time and the read analog voltage signal's derivative is computed. About 
200 to 300 values can be displayed on the Serial monitor using the Serial.print() function. The ways of storing these values 
on the memory of a microcontroller or an external FLASH/EEPROM needs to be done and must be possible to review the information 
whenever requested
