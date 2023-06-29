Project Schematic 
----------------------------

![ScreenShot project sch](https://github.com/gavinlyonsrepo/LCR_meter/blob/main/documentation/images/LCR_meter.png)

Example Output
-----------------------------

![ScreenShot cap serail](https://github.com/gavinlyonsrepo/LCR_meter/blob/main/documentation/images/LCRmeterserial.jpg)


C Meter
-----------------------------------------------

**Test 1**

![ScreenShot cap test1](https://github.com/gavinlyonsrepo/LCR_meter/blob/main/documentation/images/cap_test1.png)

**Test 2**

![ScreenShot cap test2](https://github.com/gavinlyonsrepo/LCR_meter/blob/main/documentation/images/cap_test2.png)

**Test 3** 

![ScreenShot cap test3](https://github.com/gavinlyonsrepo/LCR_meter/blob/main/documentation/images/cap3_test3.png)

The test returns the Capacitance result and time constant.

R Meter
------------------------------------

![ScreenShot resistor](https://github.com/gavinlyonsrepo/LCR_meter/blob/main/documentation/images/R_TEST.png)


L Meter
-----------------------------------------------

![ScreenShot l](https://github.com/gavinlyonsrepo/LCR_meter/blob/main/documentation/images/L_TEST.png)


![ScreenShot seq 1](https://github.com/gavinlyonsrepo/LR_meter_arduino/blob/master/documentation/images/eq1.png)


![ScreenShot seq 2](https://github.com/gavinlyonsrepo/LR_meter_arduino/blob/master/documentation/images/eq2.png)

The comparator will turn the sine wave into a square wave with a duty of 50%(see fig 9 in 
[datasheet](https://www.onsemi.com/pub/Collateral/LM393-D.PDF)),  The microcontroller measures the signal , This measurement can then be doubled to get the period and the inverse of the period is the frequency. Since the circuit is resonating, this frequency is the resonating frequency.



