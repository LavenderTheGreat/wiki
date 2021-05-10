# Little Endian

Little endian is a method of storing bytes that stores them in reverse order (``01 02 03 04`` becomes ``04 03 02 01``), meaning the most significant byte is at the far end of the number rather than the beginning of it.

Sonic Battle stores its integer number data in little endian as it can provide optimisations when doing addition and subtraction, where the least significant byte is required to start the operation, meaning you can do the operation as you read the number.