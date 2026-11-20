# Jakub Rosiński

Computer science student in Lublin. I program in C# and Python, and I build games in Unity. I work with MySQL, MariaDB, PostgreSQL, and MongoDB, and I design and call REST APIs. That mix shows up in device control over Bluetooth and in gameplay code for an engineering thesis.

[LinkedIn](https://www.linkedin.com/in/jakubrosinski04/) · [jakubrosinski.ddns.net](http://jakubrosinski.ddns.net)

`C#` `Unity` `Python` `MySQL` `MariaDB` `PostgreSQL` `MongoDB` `REST`

## Proud Projects

**[PyBricksDualSense](https://github.com/BlanKu/PyBricksDualSense)** · Python, BLE, Pybricks, MIT  
Real-time remote control of a LEGO SPIKE Prime hub from a DualSense pad.  
`remoteControllerPS5.py` finds the hub with Bleak, waits for a `rdy` handshake, and writes 3-byte commands (`fwd`, `rev`, `stp`, turns) to the Pybricks GATT characteristic (`0x06` + payload). `hubCode.py` polls `stdin` in MicroPython and drives two motors. Direction comes from the triggers and D-pad via `pydualsense`.

**Slime_Island** · Unity, C# · engineering thesis, in progress  
Unity game written as an engineering thesis. The repository and design stay private until the scope is fixed.
