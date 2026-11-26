# Interrupt Driven Keypad Control

[Repository overview](../README.md)

Respond to an external interrupt by decoding a key and sending the selected message.

## Implementations

This version enters its handler through an interrupt. An interrupt return resumes the interrupted program; it is different from repeatedly polling a key in the main loop.

| Implementation | Input | Output |
| --- | --- | --- |
| [External Interrupt Number Words](External%20Interrupt%20Number%20Words/README.md) | Keyboard encoder | LCD / serial by selected branch |
