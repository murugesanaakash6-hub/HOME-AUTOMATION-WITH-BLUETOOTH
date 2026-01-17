# HOME-AUTOMATION-WITH-BLUETOOTH

"COMPANY": CODTECH IT SOLUTIONS

"NAME": AAKASH

"INTERN ID": CTIS0687

"DOMAIN": EMBEDDED SYSTEM

"DURATION": 4 WEEKS

"MENTOR": NEELA SANTHOSH

##This circuit represents a relay-based home automation system designed and simulated using the Wokwi platform. An Arduino UNO is used as the main controller to switch an electrical device ON and OFF through a single-channel relay module. Since Wokwi does not support real Bluetooth input, control is achieved using the Serial Monitor, which simulates wireless command input.
The relay module is connected to the Arduino with three control pins: VCC, GND, and IN. The VCC pin is connected to the Arduino’s 5V supply, GND to ground, and the IN pin to a digital output pin (D8). When the Arduino receives a command from the Serial Monitor, it sends a HIGH or LOW signal to the relay input, activating or deactivating the relay.
The load side of the relay uses the COM (Common) and NO (Normally Open) terminals. An LED with a current-limiting resistor is connected as the load, representing an electrical appliance. When the relay is energized, the NO contact closes, allowing current to flow and turning the LED ON. When the relay is deactivated, the circuit opens and the LED turns OFF.
This system demonstrates the basic working principle of home automation using relays, serial communication, and microcontroller control. The black-and-white circuit diagram clearly shows the power connections, control signals, and load wiring, making it suitable for documentation, project reports, and academic submissions.

