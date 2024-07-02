
Offgrid garage: my settings:
https://off-grid-garage.com/my-settings/

![alt ](https://off-grid-garage.com/wp-content/uploads/2024/01/screenshot-1.png)

![alt ](https://off-grid-garage.com/wp-content/uploads/2024/01/screenshot-2.png)

![alt ](https://off-grid-garage.com/wp-content/uploads/2024/01/screenshot-3.png)

![alt ](https://off-grid-garage.com/wp-content/uploads/2024/01/screenshot-4.png)

Explanation:

- Vol.Cell RCV(V): Request Charge Voltage. This voltage is the max voltage to charge, that the BMS request to the inverter. Also is the absortion voltaje, Bulk voltaje, CVL 
- Vol. Cell RFV(V): Request Float Voltage to the inverter. This voltage is the float voltage 3.35
- RFV Time(H): Timer to maintain the Float voltaje and to not try to charge again to the RCV
- Continued Charge Curr(A): CCL. 100A is the maximun, the default is 25A.
- Charge OCP Delay(S): 3. This value will reduce to 10A if you pass the 100A from the previous parameter.
- Charge OCPR Time(S): 60. 
