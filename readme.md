# CAN TO MODBUS CONVERTER

This repository provides a converting feature from CAN to Modbus protocol.

<br/>

## Requirements

```
H/W
ㄴ PCAN-USB

S/W
ㄴ PCAN-View
ㄴ Modbus Simulator
ㄴ Modbus Poll
```

<br/>

## Architecture 

CAN Protocol is a Broadcasting method, while Modbus Protocol is a Master/Slave method. Therefore, if you create a CAN Message in PCAN-View and send it, you can change it to a Modbus Message Frame and check whether it runs without error on other devices.

<br/>

## References

- <a href='https://www.port.de/fileadmin/user_upload/Dateien_IST_fuer_Migration/CAN20A.pdf'>CAN Specification 2.0 Part A</a>
- <a href='https://affon.narod.ru/CAN/CAN20B.pdf'>CAN Specification 2.0 Part B</a>
- <a href='https://www.modbus.org/specs.php'>Modbus Specifications and Implementation Guides</a>

<br/>
<br/>
<br/>

<div align='center'>
Copyright (c) 2024 HyunHwa Oh
</div>
