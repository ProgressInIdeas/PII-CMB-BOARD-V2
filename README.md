# PII-CMB-BOARD-V2


“INSERT IMAGE”

Introduction

The PII CMB V2 is a CNC breakout board for the super powerful Teensy 4.1 control board, running the equally powerful GrblHAL firmware.  The PII CMB V2 supports the following features:
    • 4 Axis Control with standard STEP/PUL, DIR, EN Pins, all supporting +5V Logic Levels.
    • Fully Isolated inputs for all Axis Limits and Control Signals with selectable voltage levels and LED indicators.
    • +12V or +24V Power Supply Connection with reverse connection protection, and power regulation onboard meeting Class A EN 55032 Emission requirements.
    • 0-5V, 0-10V, 4-20Ma, or +5V PWM Selectable Spindle Speed Control Output.
    • Spindle Direction Control with Spindle Enable Control all supporting +5V Logic Levels.
    • FLOOD, AUX0, AUX1, AUX2, capable of sinking 400mA each with selectable Onboard LED indicators.  (Used for relay control.)
    • High-Speed Isolated Spindle Pulse/Index for feedback.
    • Fully buffered External I2C interface at +5V Logic Levels with STROBE input pin available for external keypads. (Up to 6ft)
    • I2C Onboard Temperature Sensor with Over/Under Temperature ALERT LED indicator.
    • USB Host Interface Capable via an onboard USB A connector.  (Keypads, Gamepads, Etc.)
    • Ethernet 10/100 Interface Connectivity.
    • Peripheral interface for Bluetooth/WiFi modules with onboard activity LED’s, and reversible RTS and CTS pins.
    • Isolated Half-duplex RS485 interface with Auto direction, onboard ability to break isolation, and onboard activity LED’s.
    • I2C 16kB EEPROM/FRAM memory onboard. (OPTIONAL)
    • 3V Battery connector (JST-PH) for retained memory. functions (OPTIONAL)

Definitions/Capabilities:

Axis Stepper Driver Control Outputs:

Stepper Driver Outputs Include +5V Step/Pulse for X, Y, Z, A-Axis, +5V Direction Control Signals for X, Y, Z, A-Axis, +5V Enable Control Signals for X, Y, Z, A-Axis.  All buffered for driving most stepper driver boards.  Onboard Y-Axis and A-Axis teaming selection available for dual motor Y-Axis machines.

Axis Limit Inputs:

Limits for X, Y, Z, A-Axis all opto-isolated for protection from external transients, +5V or +12V input selectable.  All Axis Limits include an LED indicator showing when tripped as well as a dedicated screw terminal block and reverse connection protection. 




Estop/Probing Inputs:

PROBE & ESTOP are all opto-isolated for protection from external transients, +5V or +12V input selectable.  PROBE & ESTOP each have an onboard LED indicator showing when tripped. Dedicated screw terminal block for ESTOP & PROBE inputs.  Also, reverse connection protection for each.

GRBL Standard Control Inputs:

Dedicated FEED/HOLD & CYCLE/START Inputs are all opto-isolated for protection from external transients, +5V or +12V input selectable.  Each function has a dedicated LED indicator showing when tripped, as well as a dedicated screw terminal block and reverse connection protection.

Spindle Control I/O’s:

Dedicated Spindle Control screw terminals include: +5V Spindle Enable Output, +5V Spindle Direction Control Output.  Spindle Speed Control via selectable 0-5V, 0-10V, 4-20mA, or +5v PWM output modes.  Spindle Feedback via High-Speed Isolated and filtered A / B, & INDEX input pins.

CMB Board Power Supply(s):

+12V thru +24V power supply input with reverse voltage protection with onboard +5V (2A) and selectable +15V (0.5A) power regulator, all meeting EN 55032 Class A Emission requirements.  All power supplies/inputs have dedicated LED indicators.  Onboard +3.3V LDO for CMB functions only.  Optional onboard JST PH-Series 2 Pin connector for 3V Battery connection for retained memory functions.

USB A Host Interface:

USB A connector onboard for future Host interface connections, powered thru the Teensy 4.1. Has onboard current protection PPTC resettable fuse to 350mA.

Ethernet 10/100 Interface:

Ethernet 10/100 interface for communication with the CNC machine.

Teensy 4.1 micro-USB Interface:

Teensy 4.1 micro-USB interface for communication with the CNC machine as well as programming of the Teensy device.

Serial Interfaces:

Separate Bluetooth/Wi-Fi and Isolated Half-Duplex Auto Direction RS-485 serial interfaces. The CMB includes a pin header compatible with standard HC-05 Bluetooth modules.  RS-485 serial interface is completely isolated from the CMB, with the option to break the isolation onboard.  It also works at +5V logic levels.  RS-485 has a dedicated screw terminal block.  Both interfaces have onboard LED indicators for TX & RX activity.

I2C Interfaces:

I2C interface has a buffered interface which extends the I2C interface externally at +5V logic levels for longer signal integrity levels.  It also includes a STROBE input pin for keypad connections that require it, also at +5V level. The external I2C interface has a dedicated screw terminal block. I2C bus includes an Optional 16kB EEPROM/FRAM for data logging, an onboard Temperature sensor with ALERT LED for monitoring the working environment of the CMB and Teensy 4.1, and a standard input MUX with interrupt for receiving the ALARM pins of the motor drivers.
