# NE555-One-Minute-Timer-Circuit
NE555 One-Minute Timer Circuit 
This project demonstrates a 1-minute timer built using the NE555 Timer IC in a monostable configuration. When the push button SW1 is pressed, the timer is triggered and the output (pin 3) goes HIGH for a fixed time period. During this interval the LED turns ON, and after approximately 60 seconds, the timer automatically resets and the LED turns OFF.

The timing duration is determined by the RC network composed of R3, R2, and C1.


Why a 500kΩ Resistor (R3) is Used

The 500kΩ resistor plays an important role in reducing standby current consumption.

Reasons:
-- Lower charging current
A large resistance limits the current flowing into the timing capacitor.
-- Power efficiency
When the LED is OFF and the circuit is idle, the current through the timing network is very small.
-- Longer timing with minimal power loss
Using a large resistor allows the circuit to reach long delays without requiring very large capacitors.
This makes the circuit more energy efficient, especially for battery-powered applications.

This type of timer circuit can be used in:

•	Automatic light timers
•	Delay circuits
•	Power-saving indicators
•	Alarm or alert timing

 
