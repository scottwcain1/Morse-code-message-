# State Machine to make Morse Code Messages
This project was about building a state machine that makes an LED blink out “SOS” or “OK” in Morse code. The button press switches between the two messages, but only after the current sequence finishes. It relied on timers, interrupts, and precise GPIO control.
### Problem Solved
The challenge was handling message timing and transitions without cutting anything short. I had to manage asynchronous button input cleanly and make sure the system stayed responsive while keeping everything in sync.
### What Went Well
Having the state machine for Morse sequences that worked smoothly. Used interrupts to catch button input and toggle messages in real time
### Where I Could Improve
The code hard for me to understand at first but once I did I felt like I have learn more about coding then I have in a while. 
### Tools and Resources
TI driver libraries for GPIO, Timers, I2C, and UART. CCS (Code Composer Studio) for development and debugging. State machine patterns to cleanly manage message logic
### Transferable Skills
Solid grasp of state machines for real-time systems. Comfortable working with timers, interrupts, and peripheral communication.
## Code Design
I used defined constants for timing and made the code modular to keep it easy to update. Comments explain what each function does, and the structure makes it adaptable for future changes.
