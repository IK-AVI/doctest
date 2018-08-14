---
title:  BeoLiving Intelligence - FAQ
layout: pagetoc
---

### How to upgrade _BeoLiving Intelligence_ to PRO?

_BeoLiving Intelligence_ could be upgraded through its web interface pressing in "_BASIC_" at upper-left top bar and clicking at "_Click to 
upgrade_" link in _License type_.

### How do I get my _BeoLiving Intelligence_ IP address?

The following methods to discover _BeoLiving Intelligence_ IP are suggestions (this doesn't mean that they are the only ones):

- Use a network scanner/IP-scanner, e.g. the free-ware: Fing. The best result is obtained using a hand held device; remember to access the Wi-Fi 
network used by the _BeoLiving Intelligence_.
- Using a computer on the same network as the _BeoLiving Intelligence_ and an application that supports Bonjour discovery (e.g. the Safari browser
, avahi-browse), 
lookup for "\_hipservices.\_tcp." service and the application will discover the IP addresses of the _BeoLiving Intelligence_ in the network.
- Access to your _LAN_ router and search for the assigned IP to _BeoLiving Intelligence_. 

### How to link Alexa with your _BeoLiving Intelligence_?

Refer to our specific guide: [BeoLiving Intelligence link to 3rd party Cloud Service guide](bli-link-third-party-service.md).

### How to link IFTTT with your _BeoLiving Intelligence_?

Refer to our specific guide: [BeoLiving Intelligence link to 3rd party Cloud Service guide](bli-link-third-party-service.md).

### How can I control my devices with Alexa? What to say?

Refer to our specific guide: [BeoLiving Intelligence Alexa skill guide](bli-alexa.md).

### Alexa does not understands when trying to control an specific device

Sometimes, devices name are not suitable for _Alexa_ to understand. Some workarounds to fix this issue are described at [BeoLiving Intelligence Alexa skill guide](bli-alexa.md).

### Can't link IFTTT or Alexa with _BeoLiving Intelligence_

Make sure you first enabled _Remote Access_ of your _BeoLiving Intelligence_ through _BeoLiving App_. Refer to [BeoLiving Intelligence Quick Setup
 guide](bli-quick-setup-guide.md) for a detailed description. 

### How do I report an issue with my _BeoLiving Intelligence_?

Refer to our specific guide: [BeoLiving Intelligence Troubleshooting guide](bli-troubleshooting.md). You will find instructions about how to proceed in case
 of error reporting.

### My _BeoLiving Intelligence_ is not responding, what should I do?

Refer to our specific guide: [BeoLiving Intelligence Troubleshooting guide](bli-troubleshooting.md). You will find instructions to follow in case your 
_BeoLiving Intelligence_ isn't responding or isn't returning to a normal operation mode.

### Can not establish connection with a certain HA system, what should I do? 

Check that _BeoLiving Intelligence_ and the HA system are connected to the same _LAN_ network. Check connectivity for each system (e.g.: ping 
_BeoLiving Intelligence_ and HA system).

At _Systems_ section of _BeoLiving Intelligence_ web interface, check that _Connection settings_ of the HA system are correctly configured.

Try to provoke a system reset of the HA system and check if connection can be established.

If connection can not be restored, follow the instructions at [BeoLiving Intelligence Troubleshooting Guide](bli-troubleshooting.md) of how to create and 
send a _Service report_ of your _BeoLiving Intelligence_.

### How can I find a specific source of an A/V device in _BLApp_?

Sources showed in _BLApp_ are managed in the _Interface_ section of _BeoLiving Intelligence_ web interface. Selecting the device owner of 
the specific source, check that the source has not the checkbox "_Hidden_" selected. For more information regarding configuration of user 
interfaces check _Interfaces_ section of [BeoLiving Intelligence PRO User Guide](bli-pro-user-guide.md). 

### What does the BeoLiving Intelligence_ Led color/patter means?

_BeoLiving Intelligence_ Led color displays the actual state of your _BeoLiving Intelligence_. The combination between color and pattern represent an specific _BeoLiving Intelligence_ state:

| Activity                       | LED state                  |
|--------------------------------|----------------------------|
| Normal operation               | Constant Green             |
| Critical error                 | Flash Red / Yellow         |
| Firmware update                | Quick flash Green          |
| Loading configuration          | Quick flash Green          |
| Waiting for User confirmation  | Quick flash Green / Yellow |
| User confirmation acknowledge  | Constant Yellow            |
| Boot                           | Transition Red / Yellow    |


### What are the upgrades in the _BeoLiving Intelligence PRO_?

_BeoLiving Intelligence_ has most of his capabilities reduced. Upgrading your _BeoLiving Intelligence_ to _BeoLiving Intelligence PRO_, will let you experience all your _BeoLiving Intelligence_ can offer, as the next table
 shows:

| Functionalities                                                                                | _BeoLiving Intelligence_ | _BeoLiving Intelligence PRO_ |
|------------------------------------------------------------------------------------------------|-------|-----------|
| Control _B&O NetworkLink_ products                                                             | **+** |   **+**   | 
| Remote access                                                                                  | **+** |   **+**   |
| Alexa, IFTTT integration                                                                       | **+** |   **+**   |
| Configuration with _BeoLiving App_ (Limited compared with configuration through web interface) | **+** |   **+**   | 
| Control over _BeoLiving App_                                                                   | **+** |   **+**   |
| Configuration with web interface                                                               |       |   **+**   |
| Control over _WebPanel_ (Browser) and TV's _Home Control_                                      |       |   **+**   |
| Integration with _Home Automation_ systems                                                     |       |   **+**   | 
| Customization of _BeoLiving App_ intallation control                                           |       |   **+**   | 


### Can I controll my devices outside my house?

Remote access is available in all firmware versions of _BeoLiving Intelligence_. You can activate it by going to your _BeoLiving Intelligence_ settings in the _BLApp_.

### How can I control my _BeoLiving Intelligence_?

_BeoLiving Intelligence_ has multiple ways of user interfaces for control your building. From factory, _BeoLiving Intelligence_ could be controlled only by _BeoLiving App_ and _Voice_ 
(linking your _BeoLiving Intelligence_ with _Alexa_). After upgrading your _BeoLiving Intelligence_ to _BeoLiving Intelligence PRO_, control through _BeoLiving Intelligence_ web interface and _Home 
Control_ native application of Bang & Olufsen TV's becomes available.

### If the power goes off, do I lost _BeoLiving Intelligence_ configuration?

_BeoLiving Intelligence_'s configuration is persistent, so all configuration and programmation will be safe if any power-off occurs.

### What kind of devices can I control?

_BeoLiving Intelligence_ supports any _Bang & Olfusen NetworkLink_ TV or speaker device. However if you upgrade it to _BeoLiving Intelligence PRO_ it could support any of the following resources (if the driver for that Home Automation system is available and it supports the product):

* _DIMMER_: Any Light/Dimmer.
* _SHADE_: Any Curtain/Shade/Blinds.
* _THERMOSTAT_: Thermostat of 1 or 2 set points.
* _BUTTON_: Wall buttons or keypads.
* _GPIO_: General purpose input output.
* _AV RENDER_: Any _Bang & Olfusen NetworkLink_ TV or speaker device.
* _ALARM_: Alarm system. 

All of these resources are called "_Standard resources_" and most of them (less the _GPIO_'s) have a graphic representation in each user 
interface. On the other hand, _BeoLiving Intelligence_ also supports "_Custom resources_" that are system dependent and can not be represented as 
a standard resource. Those don't have a graphic respresentation in user interfaces but could be controlled through _Scenes_ programming.

### How can I know which _Home Automation_ systems can be integrated?

As this market never stops growing, we don't stop integrating new _Home Automation_ systems and cloud services. The list of all supported systems 
are showed at [**System Drivers Guide**](../bli-help-files/drivers/main.md) page. For being updated with the latest news of new supported systems
 and functionalities don't miss our _[Newsletter](***LINK***)_.

### Are the firmware updates necessary?

_BeoLiving Intelligence_ comes by default with automatic firmware updates enabled,  you can choose to turn-off that option and check for firmware updates manually.  Firmware updates are highly recommended in order to avoid malfunction or abnormal
operation.

