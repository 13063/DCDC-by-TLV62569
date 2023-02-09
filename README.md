# DCDC-by-TLV62569
 a power whose input is 5V and output is 3.3V with max current 2A using TLV62569


I design it to drive my leds,whose rating voltage is 3.3V and rating current is 350mA.if voltage is higher,it will brun,the maxium voltage is 3.5V,but the power I use is 5V,so this moudule is created.
I soldered 8 leds on another PCB and test the DCDC module.however,when I turn on the power,the leds bright very lightly,the current is very tiny.I guess it could made by the lack of ground wire of the AC power.If you know what's it,pls comment,I will appreciate.
When I connect the 8 leds,the current was just 500mA,far less than predicted 2.8A,and the chip TLV62569's max output current is 2A.if I connect 1 led,current become 160mA,less than 350mA.Fortunately,the voltage between led no matter one led or eight leds,is  3.3V all the time.
