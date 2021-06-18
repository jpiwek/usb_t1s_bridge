# USB-To-T1S Bridge
USB 2.0 to Single Pair Ethernet 10Base-T1S Bridge

**USB-To-T1S Bridge** - [Link](https://)
====================================================

**Story**
------------------------
Makers developed a secure platform during COVID-19 period to support communities and device manufacturers on re-thinking security strategies for their future product roadmap. This platform design demonstrates how to protect digital assets, firmware, intellectual property and keys by design. 

  - *MCU*: SAML11 - CortexM23 with TrustZone Hypervisor [View PSA certificate](https://www.psacertified.org/products/saml11/)
  - *Secure Element*: JIL rated ATECC608A Trust & Go with pre-provisioned certificate chain, keys
  - *Programmer / Debugger*: Microchip low cost SNAP / PicKIT4
  - *Expansion Connectors*: Mikroelektronika Click / Microchip Xplained
  - *Interfaces*: FTDI USB to UART Bridge for debugging and powering the board
  - *Others*: 2x LEDs and 2x push button
  
![USB-To-T1S Bridge](images/trustify.png)
 
 **Target Markets**
------------------------
  - Smart Sensors
  - Medical 
  - Access Control
  - Touch & HMI
  - Portable applications
  - Crypto Wallets

**Examples**
------------------------
All examples are built with Microchip MPLAB-X & Harmony v3. Those give you a good starting point for your own projects.
  - "Board Test": [Go to example](https://github.com/jpiwek/trustify/tree/master/software/examples/Board_Test)
  - ATECC608 Secure Element Certificate Chain Verfy - This example show you the methods and the procedure to read and to verify the TNG (Trust and Go - preporvisioned secure element) certificate in the secure element: [Go to example](https://github.com/jpiwek/trustify/tree/master/software/examples/Trust_and_Go)

To setup the toolchains, please go [here](https://github.com/jpiwek/trustify/blob/master/software/examples/README.md)

**Details**
------------------------

![USB-To-T1S Bridge](images/overview.png)
