# RFID-lock-rasberry
This method opens the Raspberry Pi’s serial port, and loops continuously to read a RFID card/tag. It is the primary method of the Pi-Lock, and starts when the RPi boots up. If a card is found, it calls the findTag() function, which in turn searches in the local SQLite database  for the card, and then determines if the scanned card if valid for entry.
