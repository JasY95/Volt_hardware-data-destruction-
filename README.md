# Volt_hardware-data-destruction-
An open source diagram of autonomous data destruction

I will soon upload full diagrams of how to print and assemble a circuit that will automatically interact with any attached SATA interface to destroy all host data if certain conditions are not met. 
This facilitates a true dead-man switch that ensures the complete destruction of held data if the host is not present. 
This is a USB based protocol, and relies on the presence of a USB data input, internally, ideally. 

If the conditions are not met, then this circuit hijacks the SATA connection, causes mass corruption and then discharges the full capacity of the attached capacitor to permanently destroy the controller. 

This is intended for desktop implementation only. 
