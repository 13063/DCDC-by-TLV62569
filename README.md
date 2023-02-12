# DCDC-by-TLV62569
 A DCDC module whose input is 5V and output is 3.3V with max current 2A using TLV62569


I designed it to drive my leds,whose rating voltage is 3.3V and rating current is 350mA.If voltage is higher,it will burn,the maxium voltage is 3.5V.The power I use is 5V,so this moudule was created.
I soldered 8 leds on another PCB and test the DCDC module.However,when I turn on power and keep EN1 high,the leds was surprisingly bright very weakly,the current was very tiny.Because if EN1 was high the PMOS will cut off making TLV62569 no input.I guess it may caused by the lacking ground wire of the AC power.If you know what's cause it,pls comment,I will appreciate.
When I connect the 8 leds,the current was just 500mA,far less than the chip TLV62569's max output current 2A.if I connect 1 led,current become 160mA,less than 350mA.Fortunately,the voltage between led no matter one led or eight leds is 3.3V all the time.
