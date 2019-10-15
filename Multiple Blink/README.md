## Multiple Blink

This code instantiates instead of one led, now 2 Led's (1.0 & 2.1 for the G2), (1.0 & 9.7 for the FR6989). The code is not in low power mode, therefore it will run through the code sequentially, and eventually loop back. In order to make both led's blink at different rates we put 2 delays and blinked the same led twice before the other one was blinked once.