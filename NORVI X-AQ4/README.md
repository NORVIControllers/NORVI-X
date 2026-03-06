# NORVI X-AQ4
## 4-channel analog output expansion module

The NORVI X-AQ4 provides 4 analog outputs: 2 voltage outputs (0–10 V) and 2 current outputs (4–20 mA), managed by a dedicated 12-bit DAC on the onboard STM32 microcontroller. 
This setup offloads timing-critical signal generation from the main CPU, ensuring high stability and precision.

## Testing Instructions
- The module has **2 voltage output ports** and **2 current output ports**.
- Connect **GND** and **Analog GND** together.
- Use the **Serial Monitor** to input voltage or current values within the supported range.
 ### Example Input
          Enter values in the Serial Monitor like this:
          CH1=5
          CH2=10
          CH3=4
          CH4=20
- Ports AOUT1 and AOUT2 correspond to **voltage outputs**, while ports AOUT3 and AOUT4 correspond to **current outputs**.
- You can verify the output values using a **multimeter**, which should match the values entered in the Serial Monitor.

Datasheet : https://norvi.io/docs/norvi-x-aq4-datasheet/
