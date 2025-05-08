<h1> DEV BOARD with TEMPLOGGER v1.0.0</h1>

This Design is for temperature data logging application, which is implemented using a simple, low power Microcontroller.

· The data is logged into a SD card mounted on the PCB that is implemented using SPI communication protocol.

· This design makes use of a Positive Temperature Co-efficient (PTC) Silicon based Thermistor [TMP36GT9Z].


· This PCB is Battery powered and also includes a Battery Management System (BMS) for determining the battery charge and health.

· A Relay and a Buzzer is also implemented for any actuator switching and warning application.

Main Components used:

1. MCU: STM32G030F6P6 [TSSOP20]

2. Thermistor: TMP36GT9Z [SOT23]

3. BMS: BQ27427YZFR [BGA-IC]

4. SD card.


Indications of the LED lights:

1. Blue: Indicates Power on/ Battery connected state.

2. Red: Indicates Programming/Debug process.

3. Green: Indicates Data being written onto the SD card i.e. Data-logging process.


Functions of the PUSH buttons:

1. BMS: wakes up the BMS from sleep mode.

2. RESET: Reset’s the MCU in case of any errors.


You can find all the design files and necessary datasheets above.

Thankyou


-Regards
CHANNABASAVA H
