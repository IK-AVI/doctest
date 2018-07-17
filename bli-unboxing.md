# Un-boxing BeoLiving Intelligence

|    Date      | Author       | Comments             |
|--------------|--------------|----------------------|
| [2018-05-29] | Aldo Vignone | First version        |    

## What´s in the Box

After opening the box of BeoLiving Intelligence you will find:

+ BeoLiving Intelligence hardware.
+ Wall bracket for BeoLiving Intelligence.
+ AC Power Supply.
+ Quick setup guide.

## Connection Panel

Located on the back of the BeoLiving Intelligence:

+ *Power*: Powers the BeoLiving Intelligence. 
+ *USB Port*: Used for service purpouses.
+ *System Reset Button*: After being pressed during 8 seconds, a system reset will occur.
+ *RJ 45 Connector*: Used to attach an Ethernet cable to connect to a local network (*PoE* capable). 

![Ports](pictures/ports.png)

## First run

By default, BLI comes configured in DHCP mode. This means it gets its IP address from the router it is connected to. To configure static IP address, please refer to _"BeoLiving Intelligence User Guide"_.

Follow the next steps to let your BeoLiving Intelligence running:

1. Connect BLI to your LAN through his RJ45 ethernet port.
2. Power your BLI using the AC Power supply or PoE.
3. Wait until User LED stay solid on Green (this indicates normal operation).
4. Start experiencing what your BeoLiving Intelligence can do with BeoLiving App.

## User Led and Button

+ *User LED*: The User LED is used to signalize present state of BeoLiving Intelligence from the use of colours and ON-OFF patterns combination. Colours could be Green, Red or Yellow and patterns Solid, Flash and Quick Flash. For more information about different BLI LED states refer to [*Led States*](#led-states) section.
+ *User Button*: This button is intended for user confirmation and button functions input. For more information refer to _Button Functions_ section in _BeoLiving Intelligence User Guide_.

![Ports](pictures/bli.png)

## Led States

BeoLiving Intelligence box has a LED which is used to display system status
and feedback for user input.

| Activity                       | LED state                  |
|--------------------------------|----------------------------|
| Normal operation               | Constant Green             |
| Critical error                 | Flash Red / Yellow         |
| Firmware update                | Quick flash Green          |
| Loading configuration          | Quick flash Green          |
| Waiting for User confirmation  | Quick flash Green / Yellow |
| User confirmation acknowledge  | Constant Yellow            |
| Boot                           | Transition Red / Yellow    |

Table: BLI states versus LED state
