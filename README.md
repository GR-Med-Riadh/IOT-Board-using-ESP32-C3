# IOT-Board-using-ESP32-C3
Hello everybody, i Hope you find this message well.Every day we hear about fire problems in Our homes or problems with security, don't forget old people who live alone. Sometimes when we hear about these problems we don't  have time to react. But now with advanced technologies we can find a solution.
JLCPCB is a company that constructs PCBs and prints 3D mechanical designs, they give us great offers with cheap prices for high quality precision PCBs. I would like to thank JLCPCB for their sponsorship and for supporting me in creating and innovating schematics, and improving my PCBs designs.
Our solution based on electronics board that contain components to do multiple tasks in our home to make it smarter, we used dht11 sensor to calculate temperature and humidity
using one wire communication.
The basis of 1-Wire technology is a serial protocol using a single data line plus ground reference for communication.
To make actions  using motors, air fans or something else we make an electronic bridge that contains a transistor and relay.The transistor is to switch from 3.3v to 5v, to control the relay and then the last one will apply input tension on our actuator to get an action.
For this application we choose ESP32-C3,it’s a 32bits microcontroller architecture RISC-V.  the reason why we choose an ESP32 its because we need to use Wifi and Bluetooth technology to connect wifi or share data,but we choose it especially because it contains a high wifi security.
https://jlcpcb.com/HAR


