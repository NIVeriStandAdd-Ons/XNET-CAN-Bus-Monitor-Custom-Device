## XNET CAN Bus Monitor Custom Device ##

The **XNET CAN Bus Monitor Custom Device** allows you to monitor XNET CAN ports in your system.

### LabVIEW Version ###

This was written in LabVIEW 2014, but none of the functionality is version dependent so it could be converted to earlier versions.  

### Built Availability ###

Built versions of this device are not available. Download the source and build it to use this device.

### Quality, Limitations ###

This custom device is of good quality but has only been tested on RT PXI. It should work on any RT or Windows target with XNET CAN devices.

The custom device currently only provides bus load and peak bus load for the specified port. However, other statistics seen with the NI XNET Bus Monitor are also available within this code, they just aren't exposed. 

Note that this custom device currently only supports XNET CAN, but could support XNET LIN with low effort and XNET FlexRay with high effort.

This custom device currently requires the user to add instances for each XNET CAN Port to be monitored, and specify the parameters of the port. It could be modified, with low effort, to automatically detect XNET CAN ports and retrieve their parameters.  

### Dependencies ###

NI-XNET

### License ###

*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*