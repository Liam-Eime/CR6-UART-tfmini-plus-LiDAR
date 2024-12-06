# CR6-UART-tfmini-plus-LiDAR
Repository for my work with a Campbell Scientific CR6 data logger in CRBasic for UART communication with a TFmini Plus LiDAR

### Configuration requirements
In LoggerNet, the Dev Config Utility must be used to set the ComC1 control port to LVTTL in order for the serial data received to match what is expected.

### The Program
- Establishes the ports C1 and C2 for serial communication.
- Reads the serial data from the LiDAR sensor, obtaining distance, signal strength and internal chip temperature.
