# Arduino-DoorLock
Hello everyone,



After deciding to pursue both software and hardware programming alongside my university studies, I made the decision to purchase an Arduino board and start working on various projects. The first step I took was buying a breadboard, an Arduino Uno R3 board, a full-size breadboard, 5 LEDs, and a mini project to learn Arduino programming. After that, I decided to work on a practical project, which is the smart card lock. I have uploaded the project codes for you to see.



The basic idea of the project is that when you hold a card in front of a module, a lock opens. I have also provided images for you to see.



Here's what you'll need for this project:

- 1 Arduino Uno R3 board (you can use other boards as well, but I used this one)

- 1 breadboard (any size you prefer, but I used a full-size one)

- 1 12V lock

- 1 RFID-RC522 module

- Several male-to-male jumper wires

- 1 USB Type B to USB cable

- 3 LEDs

- 3 220-ohm resistors

- 1 10k resistor

- 1 N-type MOSFET



Please refer to the provided image for the circuit connection. Everything is clear in the technical diagram, but feel free to ask me any questions you may have.



Note that you will also need a soldering iron, but it's only required for a small one-time task, which is connecting the pins of the RFID module.



First, download the RFID module library and add it to your Arduino software by going to Sketch > Include Library > Add .zip Library. Once successfully added, it's time to test the RFID module. The library comes with a sample code for testing. Go to File > Examples > MFRC522 > DumpInfo. If you receive the "OK" message, you can proceed to run the entire project code, and it will be connected.



I hope you find this information helpful. If you have any further questions, feel free to ask!
