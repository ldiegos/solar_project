# Victron smart shunt 500A/50mv Configuration

Starting with offgrid garage configuration (https://off-grid-garage.com/my-settings/)

![https://off-grid-garage.com/my-settings/](https://off-grid-garage.com/wp-content/uploads/2023/01/smart-shunt-settings.jpg)

I want to have a place to store the configuration from my devices and all the changes that i made or will make in the future.

### Notes:
- Discharge floor: 0% this will increase the bottom percentaje of the 0% SOC to leave some battery free.
- Peukert exponent: this is for lead-acid batteries, leave it as is.
- Charge efficient factor: leave the default.
- Current threshold: Start meassurement over this value. Leave default.
- Time-to-go averaging period: Last minutes to calculate the time to empty the battery. Leave default.


Reseting smart shunt to 100SOC:

- Charged voltaje: 55.0v -> 3,43/cell
- Tail current: Battery capacity * 1.50% = (864*1,5)/100 ) = 12.96A
- Charge detection time: 5m

I will go with:

- Charged voltaje: 55.2v -> 3,45/cell
- Tail current: Battery capacity * 0.50% = (320*0,5)/100 ) = 1.6A
- Charge detection time: 10m

# Historical changes
## 2024-06-28

- Charged voltaje: 55.2v -> 3,45/cell
- Tail current: Battery capacity * 0.50% = (320*0,5)/100 ) = 1.6A
- Charge detection time: 10m

- Battery capacity: 320Ah
- Discharge floor: 0%

