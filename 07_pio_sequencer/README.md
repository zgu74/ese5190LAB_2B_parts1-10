# Lab-2B-Part-7  
As what we do in P6, we used I2C to get the data from APDS9960, and we implemented other core1 to communicate with APDS9960 continuously.  
When we pressed the button, we can modify the value in register. This program captures samples from a group of pins, at a fixed rate, once a trigger   condition is detected (level condition on one pin). The samples are  transferred to a capture buffer using the system DMA.
