<h1>I2C Device Address Finder</h1>

 ### [YouTube Demonstration](https://youtu.be/9OWql6b_wj0)

<h2>Description</h2>
This Arduino code is designed to scan for I²C devices connected to the system. It utilizes the Wire library to communicate with I²C peripherals and detects their addresses by sending transmissions to every possible I²C address (ranging from 1 to 127). When a device responds without errors, its address is displayed in hexadecimal format via the Serial Monitor. This I²C scanning tool is crucial for debugging and verifying connections in projects involving multiple I²C devices. Many I²C sensors, displays, and other peripherals need to have their addresses correctly identified to communicate with them in an Arduino sketch. Incorrect or unknown I²C addresses can lead to device miscommunication or failure to operate, which can be challenging to troubleshoot manually.
<br />


<h2>Environments Used </h2>

- <b>Arduino IDE</b>

<h2>Parts List</h2>

<ul>
  <li><strong>Arduino Uno</strong>
    <ul>
      <li>Manufacturer: Arduino</li>
      <li>Specifications: ATmega328P, 16MHz, 5V, 32KB Flash</li>
      <li><a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/ref=sr_1_1?th=1">Arduino Datasheet</a></li>
      <li>Supplier: Amazon</li>
    </ul>
  </li>
  <li><strong>LCD Screen</strong>
    <ul>
      <li>Manufacturer: Soldered</li>
      <li>Specifications: 16x2 characters, 3.3V, HD44780 Controller</li>
      <li><a href="https://www.mouser.com/ProductDetail/Soldered/333171?qs=QpmGXVUTftF%2F5vBtqVXjsQ%3D%3D">LCD Datasheet</a></li>
      <li>Supplier: Mouser</li>
    </ul>
  </li>
  <li><strong>I2C Backpack Module for LCD</strong>
   <ul>
     <li>Manufacturer: Comimark</li>
     <li>Specifications: 5V, I2C Interface, PCF8574T IC</li>
     <li><a href="https://www.amazon.com/Comimark-PCF8574-PCF8574T-Expander-Raspberry/dp/B07X3KWQZ7/ref=sr_1_4">I2C Backpack Datasheet</a></li>
     <li>Supplier: Amazon</li>
   </ul>
  </li>
