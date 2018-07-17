# BeoLiving Intelligence - FAQ

## Terminology

+ _BeoLiving Intelligence_: Khimo home automation Controller.
+ _BLI_: Alias for BeoLiving Intelligence.
+ _BLApp_: BeoLiving App.
+ _NL_: Network Link.
+ _LAN_: Local Area Network.
+ _DHCP_: Dynamic Host Configuration Protocol.
+ _HA_: Home Automation.

## Where can I find documentation related to _BLI_ usage and configuration?

All documents regarding _BLI_ usage, configuration and programming are accessible at [](****LINK****).

## How to upgrade _BLI_ to PRO?

_BLI_ could be upgraded through his web interface pressing in "_BASIC_" at upper-left top bar and clicking at "_Click to 
upgrade_" link in _License type_.

## Can't get my _BLI_ IP address, what can I do?

The following methods to discover _BLI_ IP are suggestions (this doesn't mean that they are the only ones):

- Use a network scanner/IP-scanner, e.g. the free-ware: Fing. The best result is obtained using a hand held device; remember to access the Wi-Fi 
network used by the _BLI_.
- Using a computer on the same network as the _BLI_ and an application that supports Bonjour discovery (e.g. the Safari browser
, avahi-browse), 
lookup for "\_hipservices.\_tcp." service and the application will discover the IP addresses of the _BLI_ in the network.
- Access to your _LAN_ router and search for the assigned IP to _BLI_. 

## How to link Alexa, Google Home, IFTTT with your _BLI_?

Refer to our specific guide: [BeoLiving Intelligence link to 3rd party Cloud Service guide](****LINK****).

## I noticed a malfunction/issue of my _BLI_ current operation, how to and where to report this error?

Refer to our specific guide: [BeoLiving Intelligence Troubleshooting guide](****LINK****). You will find instructions about how to proceed in case
 of error reporting.

## My _BLI_ is not responding, what should I do?

Refer to our specific guide: [BeoLiving Intelligence Troubleshooting guide](****LINK****). You will find instructions to follow in case your 
_BLI_ isn't responding or isn't returning to a normal operation mode.

## Can not establish connection between a certain HA system and _BLI_

Check that _BLI_ and the HA system are connected to the same _LAN_ network. Check connectivity for each system (e.g.: ping 
_BLI_ and HA system).

At _Systems_ section of _BLI_ web interface, check that _Connection settings_ of the HA system are correctly configured.

Try to provoke a system reset of HA system and check if connection can be established.

If connection can not be restored, follow the instructions at [BeoLiving Intelligence Troubleshooting Guide](****LINK****) of how to create and 
send a _Service report_ of your _BLI_.

## Can not find specific source of A/V device in _BLApp_

Sources showed in _BLApp_ are managed in the _Interface_ section of _BLI_ web interface. Selecting the device owner of 
the specific source, check that the source has not the checkbox "_Hidden_" selected. For more information regarding configuration of user 
interfaces check _Interfaces_ section of [BeoLiving Intelligence PRO User Guide](****LINK****).

## _BLI_ Led color changed it's state, how to know what's happening?  | How to interpret _BLI_ Led color/pattern?

_BLI_ Led color displays the actual state of your _BLI_. The combination between color and pattern represent an specific _BLI_ state:

| Activity                       | LED state                  |
|--------------------------------|----------------------------|
| Normal operation               | Constant Green             |
| Critical error                 | Flash Red / Yellow         |
| Firmware update                | Quick flash Green          |
| Loading configuration          | Quick flash Green          |
| Waiting for User confirmation  | Quick flash Green / Yellow |
| User confirmation acknowledge  | Constant Yellow            |
| Boot                           | Transition Red / Yellow    |
