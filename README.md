# Network

This repository provides network protocol(e.g. CAN, Modbus) materials to understand BMS(Battery Management System) architecture.

## What is Network? 

Eletronic devices related to BMS communicate information through protocols. Information can be used to monitor BMS and manage battery status.

## Protocol Types

Modbus is simpler and more suitable for small systems with fewer devices, while CAN bus is more robust and more suitable for large systems with many nodes and high-reliability requirements. Both protocols have pros and cons and are used in different applications depending on the requirements.

### CAN
- Bus-based communication protocol developed for the automotive industry in the mid-1980s but has since been widely adopted by other industries. 
- Broadcast architecture where all nodes on the bus receive the same message and only the nodes that need the message process it. 
- More advanced protocol than Modbus and supports error detection and correction, message prioritization, and data rate negotiation. 
- Operate over multiple physical layers including twisted pair, fiber optics, and wireless.


### Modbus

- A serial communication protocol first introduced by Modicon in 1979.
- Widely used in industrial automation for communication between programmable logic controllers (PLCs) and other devices such as sensors, HMIs, and drives. 
- Master-slave architecture where the master initiates communication with the slave to retrieve data or send commands. 
- Simple ASCII or binary protocol and can operate over RS-485 or TCP/IP networks.

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