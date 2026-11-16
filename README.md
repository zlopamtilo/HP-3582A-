This paper presents a low-cost implementation of an HP-IB (GPIB, IEEE 488) interface based on the open source AR488 firmware running on an Arduino Nano microcontroller. HP-IB is a short-range, 8-bit parallel, multi master digital interface bus used for remote control and data acquisition between laboratory instruments and 
controllers. In this work, the HP 3582A spectrum analyzer serves as a case study.

The developed system converts data from the GPIB bus to USB serial communication. A graphical user interface (GUI) 
application was designed in the MATLAB App Designer environment. The application utilizes HP-IB commands to 
enable instrument connection, parameter configuration, data acquisition, graphic spectrum display, and export of the 
measured data in ASCII format.

The proposed solution demonstrates how the operational lifespan of legacy laboratory instruments can be successfully 
extended while allowing their seamless integration and automation in modern laboratory environments. The obtained 
results confirm reliable communication, accurate data transmission, and a substantial expansion of the HP 3582A’s 
functionality under contemporary laboratory conditions
