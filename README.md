# Antithesis EPP/LOP Onboard Power Supply

![printer pic](https://github.com/antithesisengineering/Antithesis-EPP-LOP-Onboard-Power-Supply/blob/main/Pictures/PSUrender.png?raw=true)


## Description 
An onboard power supply compatible with all Antithesis printers which serves as a far more convenient, compact, and portable solution when compared to the external supply. It replaces the front foot assembly and can either route a cable through the side of the MCU enclosure or less ideally to the XT60 connector on the side. It can use either the 200W or 300W 24V EPP or LOP series of power supply. The LOP series is newer and slightly more compact but both supplies are often in short supply so obtain whichever one you can. I would consider the cooling fan to be mandatory. There are three options for powering it. Power it using a lead attacked to one of the 24V outputs, a spare fan port on your mainboard routing the fan cable back into the power supply, or via the fan connector on the PSU itself. However, you will need a 12V fan and an additional connector for that option. As it stands there are no assembly instructions but I will provide some pictures, the CAD, and a BOM complete with links for the harder to find stuff. 


## Max output
It is worth noting that the EPP and LOP are only rated for their maximum output with a 10CFM fan. As the 5015 provides approximately 30-50% of that, the maximum constant output will likely be prorated somewhat. The supply has been tested at a max constant output of 180W for 8 hours using a EPP-200-24 and a 5.5CFM 5015 fan. It performed well and didn't fault out during the test. This likely isn't a concern as that is equivalent to running both heaters at maximum for 8 hours straight. An unrealistic scenario that if real would present far bigger concerns than a melting PSU. Realistically the printer draws about 75W while printing.


## Disclaimer
WARNING: This project involves working with live high-voltage AC, which can cause serious injury, fire, or death if handled improperly. By using the information and/or design files in this repository, you acknowledge and accept full responsibility for your own safety. You are also responsible for compliance with all applicable local electrical codes, regulations, and safety standards.

You must disconnect all power sources and ensure that all capacitors or components capable of storing energy are fully discharged before opening, servicing, or modifying any part of the power supply.

The author(s) assume no responsibility or liability for any injury, damage, or consequences resulting from the use or misuse of this project.
