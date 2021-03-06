### EspPlug ###

31 x 17 mm ~ 0.9 sqin


#### Parts ####

|  # | Part name                        | RefDes  | DigiKey                    |
|---:|----------------------------------|---------|----------------------------|
|  2 | C 47pF, X7R (0805)               | C1 C2   | 399-7158-1-ND              |
|  1 | C 10nF /16V NP0 (0805)           | C3      | 1276-2984-1-ND             |
|  2 | C 100nF, X7R (0805)              | C4 C5   | 399-1170-1-ND              |
|  2 | C 4.7uF /16V X5R (0805)          | C6 C7   | 1276-1065-1-ND             |
|  2 | DS LED (0805)                    | DS1 DS2 | 475-1415-1-ND              |
|  1 | J Socket 2x4                     | J1      | S7072-ND                   |
|  1 | L Ferrite 40Ohm (0805)           | L1      | 445-2201-1-ND              |
|  1 | P USB A, plug, horizontal        | P1      | WM17118-ND                 |
|  2 | R 27, 0.125W (0805)              | R1 R2   | RMCF0805FT27R0CT-ND        |
|  2 | R 1K, 0.125W (0805)              | R3 R4   | RMCF0805FT1K00CT-ND        |
|  2 | R 10K, 0.125W (0805)             | R5 R6   | RMCF0805FT10K0CT-ND        |
|  1 | U FT230XS-R (SSOP-16)            | U1      | 768-1135-1-ND              |
|  1 | VR MCP1700 (SOT-23)              | VR1     | MCP1700T3302ETTCT-ND       |

Optionally: 1/2" heat-shrink tubing, 28mm


#### Jumpers ####

JP1 and JP2 control whether GP0 pin of ESP8266 module. At most one jumper
should be soldered at any time. If connected to GND, ESP8266 module will enter
firmware update mode every time it is plugged in. If GP0 is connected to RTS#,
firmware update can be programmatically controlled; i.e. when RTS is high,
firmware update will be enabled and when RTS is low, normal operation will
proceed. Both these jumpers can be left disconnected if no firmware upgrade
functionality is needed.


#### Serial port ####

Parameters for serial port are 115200,8,N,1.
