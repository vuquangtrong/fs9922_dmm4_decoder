# Enable RS232 Communication on Digital Multimeter

My DMM is Twintex TM287 (3 5/6 digit True RMS multimeter, 6000 counts with Analog bar), which uses [FS9922-DMM4](https://www.ic-fortune.com/upload/Download/FS9922-DMM4-DS-13_EN.pdf) IC from Fortune Semiconductor Corp., This IC is also used in the DMM UNI-T UT61D. The DMM UNI-T UT61D comes with RS232 function, with a PC applicatiion to show and log mesurated values; however, Twintex doesn't support it.

I enabled the RS232 Communication by adding an opto and two resistors as below:

<img src="/rs232_txd.png?raw=true"><br>

<img src="/rs232_soldered.png?raw=true"><br>

<img src="/rs232_to_usb.png?raw=true"><br>

Here is the result:

<img src="/dmm_decoder_with_graph.png?raw=true"><br>
