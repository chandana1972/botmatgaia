# Install Bootloader #

> avrdude -p atmega644p -c avrispmkII -P usb -U lfuse:w:0xfd:m -U hfuse:w:0xdc:m -U efuse:w:0xfd:m

> avrdude -p atmega644p -c avrispmkII -P usb -U flash:w:ATmegaBOOT-botmatGAIA-m644.hex