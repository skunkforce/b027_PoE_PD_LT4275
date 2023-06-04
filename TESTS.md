# initialization test
## setup
Connected 
```mermaid
flowchart LR
  b004 --> b027 
  b027 --> r[1k between pinns 3 and 4 of osf.014 device side]
  
```
## results
initialization works on a standard PoE switch.


# current test
## setup
Connected
```mermaid
flowchart LR
  b004 --> b027 
  b027 --> r[variable resistor between pinns 3 and 4 of osf.014 device side]
  
```
Varied the output inpedence to simulate different loads. Monitored the temperature of the controller and mosfet chips with a thermal camera.
## results
Output stable up to 25 watts (which was the limmit of the test system). Temperature of the mosfet rose by 8°C. This would suggest stable operation well above the test szenario. 
