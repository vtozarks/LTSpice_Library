# Ozarks Custom LTSpice Library

Contains symbols and models not included in the standard LTSpice library.

## Usage
In LTSpice open its "Control Panel" (the "hammer" icon) and select the "Sym & Lib Search Paths" tab.  Add the location of your local copy of this repo.  

When adding "Components" to the schematic, the added location should now be an option in the "Top Directory" pulldown.  Select that location and you can now add the custom content from this library.

## Library Content
Component links will open the corresponding datasheet.

### DIODE
| Component | Manufacturer | Description |
| :---      | :--- | :--- |
| [BAS321](DataSheets/Diode/BAS321_Diode.pdf) | Nexperia | 200V General purpose diode |

### LED
| Component |  Manufacturer |Description |
| :---      | :--- | :--- |
| [LG_Q396](DataSheets/LED/Q396_LED_Green.pdf) | AMS OSRAM | SMD Standard LED - Green |
| [LY_Q396](DataSheets/LED/Q396_LED_Yelllow.pdf) | AMS OSRAM | SMD Standard LED - Yellow |

### MOSFET
| Component |  Manufacturer |Description |
| :---      | :--- | :--- |
| [DMT6012LSS](DataSheets/MOSFET/DMT6012_FET.pdf) | Diodes Incorporated | 60V N-channel enhancement mode MOSFET |

### OPTOCOUPLER
| Component |  Manufacturer |Description |
| :---      | :--- | :--- |
| [VO615A-4X](Datasheet/Optocoupler/VO615a_Optocoupler.pdf) | Vishay | High temp optocoupler, If 10mA, CTR = 160-320% |
