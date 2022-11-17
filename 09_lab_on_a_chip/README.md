### TODO:

You can now actually measure the timings you modeled in the last lab. Add APDS9960 support to your sensor, then set your system up to capture the following timing info:
- color packet delivered to PIO module
- bit delivered to WS2812 (24x/packet)
- full packet delivered to WS2812
- brightness changed on APDS

Run this experiment in both dark and light room settings (record initial ambient brightness in each case). The Neopixel should start 'off' and the ADPS9960 should be initialized with your preferred sampling rate (you may want to try a few different rates). Run the experiment for at least 100 samples at brightness settings of 0%, 25%, 50%, 75%, 100% (making sure to give the ADPS reading enough time to 'settle' each time Neopixel is turned off).

Report the observed 'jitter' based on misalignment with the free-running PWM module on the WS2012.

### Result:
All the information are shown below.
![Alt text](https://github.com/zgu74/ese5190LAB_2B_parts1-10/blob/main/09_lab_on_a_chip/part%209_blue.png)
![Alt text](https://github.com/zgu74/ese5190LAB_2B_parts1-10/blob/main/09_lab_on_a_chip/part%209_green.png)
![Alt text](https://github.com/zgu74/ese5190LAB_2B_parts1-10/blob/main/09_lab_on_a_chip/part%209_red.png)
And when we conduct the lab again in dark environment, we will find that the datas transmitted on SCL and SDA are changed.
