# Ozarks Custom LTSpice Library

Contains symbols and models not included in the standard LTSpice library.

## Usage
In LTSpice open its "Control Panel" (the "hammer" icon) and select the "Sym & Lib Search Paths" tab.  Add the location of your local copy of this repo.  

When adding "Components" to the schematic, the added location should now be an option in the "Top Directory" pulldown.  Select that location and you can now add the custom content from this library.

## Library Content

### DIODE
| Component | Manufacturer | Description |
| :---      | :--- | :--- |
| [BAS321](DataSheets/Diode/BAS321_Diode.pdf) | Nexperia | 200V General purpose diode |

### MOSFET
| Component |  Manufacturer |Description |
| :---      | :--- | :--- |
| [DMT6012LSS](DataSheets/MOSFET/DMT6012_FET.pdf) | Diodes Incorporated | 60V N-channel enhancement mode MOSFET |

### OPTOCOUPLER
| Component |  Manufacturer |Description |
| :---      | :--- | :--- |
| [VO615A-4X](Datasheet/Optocoupler/VO615a_Optocoupler.pdf) | Vishay | High temp optocoupler, If 10mA, CTR = 160-320% |
