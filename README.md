# Lithium-charger-and-LDO
This is a circuit that is used very often. It features a MCP73831 lithium charging IC capable of charging currents up to 500mA and a generic SOT23-5 LDO. I chose ultra low quiescent current mudels such as XC6215 in the 3.3V variant so the circuit can provide 3.3V all the time and last for ages


Update: version v1.1 is even smaller and contains some substantial improvements: you can switch off the LDO and the voltage divider (which will otherwise consuming power) via an external switch while still maintaining charging capability of the battery. All USB data lines are broken out to test pads.
