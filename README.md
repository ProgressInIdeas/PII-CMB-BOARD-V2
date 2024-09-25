
</head>

<body dir="ltr" style="max-width:8.5in;margin-top:0.7874in; margin-bottom:0.7874in; margin-left:0.7874in; margin-right:0.7874in; ">
<p class="paragraph-P3"> </p><p class="paragraph-P3"> </p>
<p class="paragraph-P3">“INSERT IMAGE”</p>

<p class="paragraph-P4"><span class="text-T3">Introduction</span><span class="text-T3"/></p>
<p class="paragraph-P6"> </p>
<p class="paragraph-P4"><span class="text-T2">The PII CMB V2 is a CNC breakout board for the super powerful Teensy 4.1 control board, running the equally powerful GrblHAL firmware.  The PII CMB V2 supports the following features:</span><span class="text-T2"/></p>
<ul><li><p class="P5" style="margin-left:0cm;"><span class="ListLabel_20_1" style="display:block;float:left;min-width:0.635cm;"></span><span class="text-T2">4 Axis Control with standard STEP/PUL, DIR, EN Pins, all supporting +5V Logic Levels.</span><span class="text-T2"/><span class="odfLiEnd"/> </p></li><li><p class="P5" style="margin-left:0cm;"><span class="ListLabel_20_1" style="display:block;float:left;min-width:0.635cm;"></span><span class="text-T2">Fully Isolated inputs for all Axis Limits and Control Signals with selectable voltage levels and LED indicators.</span><span class="text-T2"/><span class="odfLiEnd"/> </p></li><li><p class="P5" style="margin-left:0cm;"><span class="ListLabel_20_1" style="display:block;float:left;min-width:0.635cm;"></span><span class="text-T2">+12V or +24V Power Supply Connection with reverse connection protection, and power regulation onboard meeting Class A EN 55032 Emission requirements.</span><span class="text-T2"/><span class="odfLiEnd"/> </p></li><li><p class="P5" style="margin-left:0cm;"><span class="ListLabel_20_1" style="display:block;float:left;min-width:0.635cm;"></span><span class="text-T2">0-5V, 0-10V, 4-20Ma, or +5V PWM Selectable Spindle Speed Control Output.</span><span class="text-T2"/><span class="odfLiEnd"/> </p></li><li><p class="P5" style="margin-left:0cm;"><span class="ListLabel_20_1" style="display:block;float:left;min-width:0.635cm;"></span><span class="text-T2">Spindle Direction Control with Spindle Enable Control all supporting +5V Logic Levels.</span><span class="text-T2"/><span class="odfLiEnd"/> </p></li><li><p class="P5" style="margin-left:0cm;"><span class="ListLabel_20_1" style="display:block;float:left;min-width:0.635cm;"></span><span class="text-T2">FLOOD, AUX0, AUX1, AUX2, capable of sinking 400mA each with selectable Onboard LED indicators.  (Used for relay control.)</span><span class="text-T2"/><span class="odfLiEnd"/> </p></li><li><p class="P5" style="margin-left:0cm;"><span class="ListLabel_20_1" style="display:block;float:left;min-width:0.635cm;"></span><span class="text-T2">High-Speed Isolated Spindle Pulse/Index for feedback.</span><span class="text-T2"/><span class="odfLiEnd"/> </p></li><li><p class="P5" style="margin-left:0cm;"><span class="ListLabel_20_1" style="display:block;float:left;min-width:0.635cm;"></span><span class="text-T2">Fully buffered </span><span class="text-T4">External</span><span class="text-T2"> I2C interface at +5V Logic Levels with STROBE input pin available for external keypads. (Up to 6ft)</span><span class="odfLiEnd"/> </p></li><li><p class="P5" style="margin-left:0cm;"><span class="ListLabel_20_1" style="display:block;float:left;min-width:0.635cm;"></span><span class="text-T2">I2C Onboard Temperature Sensor with Over/Under Temperature ALERT LED indicator.</span><span class="text-T2"/><span class="odfLiEnd"/> </p></li><li><p class="P5" style="margin-left:0cm;"><span class="ListLabel_20_1" style="display:block;float:left;min-width:0.635cm;"></span><span class="text-T2">USB Host Interface Capable via an onboard USB A connector.  (Keypads, Gamepads, Etc.)</span><span class="text-T2"/><span class="odfLiEnd"/> </p></li><li><p class="P5" style="margin-left:0cm;"><span class="ListLabel_20_1" style="display:block;float:left;min-width:0.635cm;"></span><span class="text-T2">Ethernet 10/100 Interface Connectivity.</span><span class="text-T2"/><span class="odfLiEnd"/> </p></li><li><p class="P5" style="margin-left:0cm;"><span class="ListLabel_20_1" style="display:block;float:left;min-width:0.635cm;"></span><span class="text-T2">Peripheral interface for Bluetooth/WiFi modules with onboard activity LED’s, and reversible RTS and CTS pins.</span><span class="text-T2"/><span class="odfLiEnd"/> </p></li><li><p class="P5" style="margin-left:0cm;"><span class="ListLabel_20_1" style="display:block;float:left;min-width:0.635cm;"></span><span class="text-T2">Isolated Half-duplex RS485 interface with Auto direction, onboard ability to break isolation, and onboard activity LED’s.</span><span class="text-T2"/><span class="odfLiEnd"/> </p></li><li><p class="P5" style="margin-left:0cm;"><span class="ListLabel_20_1" style="display:block;float:left;min-width:0.635cm;"></span><span class="text-T2">I2C 16kB EEPROM/FRAM memory onboard. (</span><span class="text-T5">OPTIONAL</span><span class="text-T2">)</span><span class="odfLiEnd"/> </p></li><li><p class="P5" style="margin-left:0cm;"><span class="ListLabel_20_1" style="display:block;float:left;min-width:0.635cm;"></span><span class="text-T2">3V Battery connector (JST-PH) for retained memory. functions (</span><span class="text-T5">OPTIONAL</span><span class="text-T2">)</span><span class="odfLiEnd"/> </p></li></ul><p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T3">Definitions/Capabilities:</span><span class="text-T3"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T3">Axis Stepper Driver Control Outputs:</span><span class="text-T3"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T2">Stepper Driver Outputs Include +5V Step/Pulse for X, Y, Z, A-Axis, +5V Direction Control Signals for X, Y, Z, A-Axis, +5V Enable Control Signals for X, Y, Z, A-Axis.  All buffered for driving most stepper driver boards.  Onboard Y-Axis and A-Axis teaming selection available for dual motor Y-Axis machines.</span><span class="text-T2"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T3">Axis Limit Inputs:</span><span class="text-T3"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T2">Limits for X, Y, Z, A-Axis all opto-isolated for protection from external transients, +5V or +12V input selectable.  All Axis Limits include an LED indicator showing when tripped as well as a dedicated screw terminal block and reverse connection protection. </span><span class="text-T2"/></p>
<p class="paragraph-P7"> </p><p class="paragraph-P7"> </p><p class="paragraph-P7"> </p><p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T3">Estop/Probing Inputs:</span><span class="text-T3"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T2">PROBE &amp; ESTOP are all opto-isolated for protection from external transients, +5V or +12V input selectable.  PROBE &amp; ESTOP each have an onboard LED indicator showing when tripped. Dedicated screw terminal block for ESTOP &amp; PROBE inputs.  Also, reverse connection protection for each.</span><span class="text-T2"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T3">GRBL Standard Control Inputs:</span><span class="text-T3"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T2">Dedicated FEED/HOLD &amp; CYCLE/START Inputs are all opto-isolated for protection from external transients, +5V or +12V input selectable.  Each function has a dedicated LED indicator showing when tripped, as well as a dedicated screw terminal block and reverse connection protection.</span><span class="text-T2"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T3">Spindle Control I/O’s:</span><span class="text-T3"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T2">Dedicated Spindle Control screw terminals include: +5V Spindle Enable Output, +5V Spindle Direction Control Output.  Spindle Speed Control via </span><span class="text-T4">selectable</span><span class="text-T2"> 0-5V, 0-10V, 4-20mA, or +5v PWM output modes.  Spindle Feedback via High-Speed Isolated and filtered A / B, &amp; INDEX input pins.</span></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T3">CMB Board Power Supply(s):</span><span class="text-T3"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T2">+12V thru +24V power supply input with reverse voltage protection with onboard +5V (2A) and selectable +15V (0.5A) power regulator, all meeting EN 55032 Class A Emission requirements.  All power supplies/inputs have dedicated LED indicators.  Onboard +3.3V LDO for CMB functions only.  Optional onboard JST PH-Series 2 Pin connector for 3V Battery connection for retained memory functions.</span><span class="text-T2"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T3">USB A Host Interface:</span><span class="text-T3"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T2">USB A connector onboard for future Host interface connections, powered thru the Teensy 4.1. Has onboard current protection PPTC resettable fuse to 350mA.</span><span class="text-T2"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T3">Ethernet 10/100 Interface:</span><span class="text-T3"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T2">Ethernet 10/100 interface for communication with the CNC machine.</span><span class="text-T2"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T3">Teensy 4.1 micro-USB Interface:</span><span class="text-T3"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T2">Teensy 4.1 micro-USB interface for communication with the CNC machine as well as programming of the Teensy device.</span><span class="text-T2"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T3">Serial Interfaces:</span><span class="text-T3"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T2">Separate Bluetooth/Wi-Fi and Isolated Half-Duplex Auto Direction RS-485 serial interfaces. The CMB includes a pin header compatible with standard HC-05 Bluetooth modules.  RS-485 serial interface is completely isolated from the CMB, with the option to break the isolation onboard.  It also works at +5V logic levels.  RS-485 has a dedicated screw terminal block.  Both interfaces have onboard LED indicators for TX &amp; RX activity.</span><span class="text-T2"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T3">I2C Interfaces:</span><span class="text-T3"/></p>
<p class="paragraph-P7"> </p>
<p class="paragraph-P4"><span class="text-T2">I2C interface has a buffered interface which extends the I2C interface externally at +5V logic levels for longer signal integrity levels.  It also includes a STROBE input pin for keypad connections that require it, also at +5V level. The external I2C interface has a dedicated screw terminal block. I2C bus includes an Optional 16kB EEPROM/FRAM for data logging, an onboard Temperature sensor with ALERT LED for monitoring the working environment of the CMB and Teensy 4.1, and a standard input MUX with interrupt for receiving the ALARM pins of the motor drivers.</span><span class="text-T2"/></p>
</body>

</html>
