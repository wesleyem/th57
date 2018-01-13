# Limits

## Engine Limitations

### Engine Oil Pressure
|Min w/ N<sub>g</sub> below 79%	| Min w/ N<sub>g</sub> 79-94%	| Min w/ N<sub>g</sub> above 94%	| Max |
|---|---|---|---|
50 psi	| 90 psi	| 115 psi	| 130 psi except 150 immediately following cold-wx start


### Engine Oil Temperature

0&deg; to 107&deg;C

### Nf

Power On:

|Min 	| Max |
|---|---|
|97% 	|	100%|

> Note: N<sub>f</sub> overspeeds are determined on a sliding scale depending on TOT, N<sub>f</sub> percentage, and duration

Avoid Range (steady-state operation)
 - 71-88% with engine torque greater than 33%
> Note: Steady state is defined as holding N<sub>f</sub> within a 2% range
> Note: Holding N<sub>f</sub> in this range for 60 cumulative seconds requires turbine replacement and shall be avoided

### Ng RPM
Idle	|	Normal	|	Max
---|---|---
|	62% +/- 2|	59%-105%	|	106% for 15s	|

### Rotor Engagement/Disengagement Wind Limitations

![Image][figure4-2]

### Turbine Outlet Temperatures

##### During Start

| Range | Time Limit |
|---|---|
| Up to 810 &deg;C | No limit |
| 810 &deg;C to 927 &deg;C | 10s max |
| 927 &deg;C | Max |

##### During power transient

| Range | Time Limit |
|---|---|
| Up to 738 &deg;C | No limit|
| 738 &deg;C to 810 &deg;C  | 5 min |
| 810 &deg;C to 843 &deg;C | 6 sec |
| 843 &deg;C | Max |

### Fuel

 - Maintain OAT above freezing point of fuel in use
 - Min fuel reserve requirement for TH-57B/C is 10 gallons

 > Caution: Airframe and engine fuel filters may become blocked if fuel is chilled below its specific freezing point.


### Instrument Markings

![Image][figure4-3]
![Image][figure4-3-2]
![Image][figure4-3-3]

### Rotor Limits

N<sub>r</sub> 

| Power ON | Power OFF |
|---|---|
|97%-100% | 90%-107%|



### Transmission Oil System Limts

##### Pressure

|Continuous	| Min | Max |
|---|---|---|
|30-50 psi| 30|70|

 - Indications between 50-70 psi shall be documented on a MAF

##### Temperature

15&deg;C-110&deg;C

> Note: Check transmission oil pressure with twist grip `full open`

> Note: Illumination of the TRANS OIL PRESS caution light is common while the twist grip is at flight idle, however, the gauge should indicate positive transmission oil pressure.

> Note: There is no detrimental effect to the transmission system with oil pressure between 50 to 70 psi with the transmission temperature within limits.


### Torque

|Max continuous | Military power limit | Transient limit |
|---|---|---|
|85%|100% for 5 min | 100-110% for 5 sec|

### Fuel Pressure

4-30 psi

### Standby Generator Limits

> Note: With main generator on, the standby generator loadmeter should indicate 10 percent load or less. Momentary testing of standby generator under full bus load is permitted on the ground or in the air. 

Prolonged operation of the standby generator while it is the primary power supply to the essential No. 1 bus is prohibited at speeds below `65 KIAS`

### Rotor Brake Limitations

Should be applied 30-38% N<sub>r</sub> during normal operations

### Starter Limitations

> Note: If a light-off occurs within the first 20 seconds of the start sequence, the starter may be operated for 60 seconds with a 60-second cooling period. Three such attempts can be made in a 30-minute period, then wait 30 minutes to allow the starter to cool. 

Limit starter engergizing time to the following:

| Ext power | Battery |
|---|---|
25s - ON| 40s - ON
30s - OFF| 60s - OFF
25s - ON| 40s - ON
30s - OFF| 60s - OFF
25s - ON| 40s - ON
30m - OFF| 30m - OFF


### Airspeed Limits

> Note: All airspeed values are calibrated airspeed except when indicated airspeed is specifically stated

| Density Alt Feet | Max Sideward Knots | Max Rearward Knots |
|:---:|:---:|:---:|
|0-1000|25|15|
|1000-2000|20|15|
|2000-4000|15|15|
|4000-6000|10|10|
|6000-10000|5|5|

| Type | Airspeed |
|---:|:---:|
| V<sub>ne</sub> FCS OFF | 130 KIAS |
| V<sub>ne</sub> FCS ON | 122 KIAS |
| Max rate of climb | 50 KIAS |
| Min IFR speed (V<sub>min i</sub>) | 65 KIAS |
| Max airspeed with any combination of doors off | 110 KIAS |
| Max autorotational airspeed | 100 KIAS |
| Turbulence penetration airspeed | 80 KIAS |



### Altitude Limitations

#### Max operating altitude

| |3000 lbs gross weight and below | Above 3000 lbs gross weight |
|---|---|---|
|FCS OFF| 20,000' PA | 16,000' PA |
|FCS OFF| 18,000' DA | 13,000' DA |
|IFR/FCS ON | 11,500' PA | 8,500' PA |
|IFR/FCS ON | 13,500' DA | 11,000 DA |

### Climb/Descent

In IMC should not exceed 1000 fpm

### Acceleration Limits

+2.5g's to +0.5g's at maximum gross weight

### Weight Limitations

| Max gross weight         | lbs      |
|--------------------------|----------|
| internally               | 3200 lbs |
| including external cargo | 3350 lbs |







[figure4-2]: https://github.com/wesleyem/th57/blob/master/images/figure4-2.png?raw=true
[figure4-3]: https://github.com/wesleyem/th57/blob/master/images/figure4-3.png?raw=true
[figure4-3-2]: https://github.com/wesleyem/th57/blob/master/images/figure4-3-2.png?raw=true
[figure4-3-3]: https://github.com/wesleyem/th57/blob/master/images/figure4-3-3.png?raw=true