# PS_Fgen_HW

## [%version%] - %date%

> Electrical > FrontPanel
- Nothing changed (equal to v1.1)
- Updated to new project name (PS_Fgen_HW)

> Electrical > MainBoard
- Resistors added to convert 5V to 3.3V for LCD signals (A0, CS, MOSI, SCK)
- Updated to new project name (PS_Fgen_HW)
- Removed some Z-Diodes
- Removed ATX_PWR_ON signal
- Removed ATX_5V_SB input (combined VCC and +5V nets)
- Removed resistor R20 (PowerSupply, between OpAmp IC5B and transistors Q5 and Q6)
- Changed resistor values of PowerSupply current measurement circuit (R21, R22, R23)
- Moved resistor R21 of current measurement circuit to be after this circuit
- Changed power stage of PowerSupply channel
- Modified DMM circuit to use DMMRectifier PCB
- ...

> Electrical > DMMRectifier
- Initial version of DMM Rectifier with simulation

> Mechanical
- Added Standfuss parts
- Modified Seitenteil_rechts for DMMRectifier
- ...

## [v1.1] - 07.08.2020
> Electrical > FrontPanel
- Nothing changed (equal to v1.0)

> Electrical > MainBoard
- Board size decreased to 100x100 to fit JLCPCB requirements for cheapter price
- Schematic not changed

> Mechanical
- Nothing changed (equal to v1.0)

## [v1.0] - 05.08.2020
> Electrical > FrontPanel
- Initial version

> Electrical > MainBoard
- Initial version

> Mechanical
- Initial version