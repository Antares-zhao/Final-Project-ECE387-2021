# Door Access Control System
Radio-frequency identification (RFID) uses electromagnetic fields to automatically identify and track tags attached to objects. When triggered
by an electromagnetic interrogation pulse from a nearby RFID reader device, the tag transmits digital data, usually an identifying inventory
number, back to the reader. 

# Components
* Arduino UNO R3 
* MFRC 522 reader
* One Channel Relay module 
* Heavy duty electric door lock 
* Blank pvc IC cards
* Some jump wires

# Assemble
A clear picture with fully assemble is already uploaded

# How it works
The reader would check if the data is matched and send signal back to the Arduino. The Arduino would engage the one channel relay module. 
The realy module would charge the electric door lock to open. After 3 seconds delay, the relay would discharge the lock. 

# Demo
demo.mp4
