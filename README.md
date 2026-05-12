# 0-to-9--7-Segment-Display-Counter-Circuit-Simulation
The project simulates a simple 7-segment display counter that counts from 0 to 9 using discrete components in Proteus simulation software.

Components Used:
7-Segment Display, 555 Timer IC, 4026 CMOS Decade Counter, SPST Switch, Passive Components - Resistors and Capacitors

Working: 
The 555 Timer IC generates continuous pulse signals at pin 3 which is connected to the clock input of 4026 IC. After picking up signal from the clock input, the 7-Segment Display increments the value being displayed by one, which resets to 0 after 9. The frequency of pulse generation is determined by the network of resistors and capacitors connected to the 555 Timer IC. The SPST switch placed in between both the ICs controls the passage of pulse signals.
