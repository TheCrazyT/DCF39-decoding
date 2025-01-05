work in progress ...

inspired by the ccc talk: 

"BlinkenCity: Radio-Controlling Street Lamps and Power Plants" (https://media.ccc.de/v/38c3-blinkencity-radio-controlling-street-lamps-and-power-plants)

gnu radio example of decoding DCF39.

Currently only outputs the hex-part in a "valid_bytes.bin":

68 0a 0a 68 37 00 00 00 30 25 0e c4 01 19 78 16

Information about the protocol based on germany:

https://de.wikipedia.org/wiki/Funkrundsteuertechnik

TODO:

Actually decode the messages themself, and validate by checksum.