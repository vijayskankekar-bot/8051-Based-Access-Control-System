Password-Protected Access Control System (8051)

A firmware-driven security system built on an AT89C51 microcontroller that manages door access authentication using a keypad, character LCD, and motor driver in Proteus simulation.

System Capabilities:
Processes user keypad inputs and executes real-time string matching against a stored PIN.
Actuates a 12V DC motor via an L293D driver IC to control door lock mechanics upon successful authentication.
Displays live system feedback ("Correct" / "Incorrect") and status prompts on a 16x2 alphanumeric LCD.
Restricts access on invalid entry attempts, maintaining secure state handling.

Hardware Components:
Microcontroller: AT89C51 (8051 architecture)
Input Device: 4x4 Matrix Keypad (Port 1)
Display Module: 16x2 Character LCD (Ports 2 and 3)
Motor Driver & Actuator: L293D Driver IC, 12V DC Motor
Power Supply: Dual 5V (Logic) / 12V (Motor) DC

Software & Tools:
Programming Language: Embedded C
Toolchain / IDE: Keil MicroVision 5
Simulation Platform: Proteus VSM
