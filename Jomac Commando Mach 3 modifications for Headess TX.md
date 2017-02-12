This file documents the modifications done to integrate the Headless Tx into the Jomac Commando Mach 3 transmitter.

The goal is to do as little as possible modifications to the transmitter so that it can be converted back to original condition easily.


- Connect GND to Jomac PCB GND
- Connect 3V3 for pots to Orange wire (colors refer to Jomac wiring)
- Connect ST pot lightblue wire to GND (Pin 1 of IC!)
- Connect TH pot / D1 wire to GND (Pin 2 of IC!)
- Connect unused terminal of ST-trim pot to GND
- Connect wipers of ST pot, ST-trim pot and TH pot to respective Headless Tx analog inputs

Isolate the ST-trim pot:
- Disconnect one side of R14

Isolate the LED and power:
- Disconnect one side of R18

Isolate the power switch:
- Disconnect one side of L1
- Disconnect one side of C15, C16 (could stay in place, but just to be safe as it is an old capacitor)
- Disconnect one side of R19
- Connect Headles Tx switch terminals to now unused side of the switch

Power-on LED:
- Replace the LED with a high-brightness 3mm one (original LED is kept untouched, just removed from the housing and safely tucked away)