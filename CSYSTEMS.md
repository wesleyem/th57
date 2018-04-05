# TH-57C Systems

1. [Electrical](#electrical)
1. [MINISTAB](#ministab)

## Electrical

### General

![Image][systems-9-1]

**DC Power Sources**

1. Main Battery
    1. Same as ![Image][b]
1. Standby Battery
    1. 22.5V 1.8amp-hr (~1.5 hrs when fully charged)
    1. Sole purpose is to power `STBY ATT IND` in complete loss of power to ESS No. 1
    1. Nickel-cadmium dry cell
    1. Located in upper right area aft of baggage compartment rear bulkhead
1. Main Generator
    1. Same as ![Image][b]
1. Standby Generator
    1. 28V 7.5amp
1. External Power
    1. Same as ![Image][b]

**Buses**

1. Ess No. 1
1. Ess No. 2
1. Non-Ess

**AC Current**

115V System

1. Avionics Inverter
1. FCS Inverter

### Battery

Same 24V 17amp-hr SLAB as in the ![Image][b]

1. Battery Module
    1. Battery relay
    1. Remote Control Circuit Breaker (RCB)
        1. aka overload sensor
        1. located between battery and external power relay
        1. RCB can sustain 250A for 10-20s at 25&deg;C **but will trip if constant current load exceeds 125A** and battery power is removed from the BUSES
        1. After trip and cool, RCB resets itself but the `Battery Relay CB` will need to be manually reset
    1. RCB Override circuit
        1. RCB is overridden on engine start to prevent power from being taken away before a complete engine start is done.
        1. "Starter on, ___ Volts, `BATT RELAY` light on"
        1. "Starter off, time is ___ , `BATT RELAY` light out"

> Note: When the `BATT RELAY` light goes on, it's saying that the engine start is being protected by the override of the RCB to ensure power isn't prematurely removed from the system prior to complete engine start

Battery switch -> On
 - energizes battery relay and BUS TIE relay
 - powers all three BUSES

### Starter Generator

Engaging the starter switch
 - energizes the starter relay connecting the starter motor to the ESS No 2
 - energizes the igniter circuit

### Main Generator System

With the Generator `ON` all three BUSES are powered

### Voltage Regulator

1. Regulates voltage to constant 28V
1. Protects from over and undervoltage conditions
    1. deenergizes generator relay disconnecting the generator from the BUSES
    1. BUS TIE relay will open removing battery power from the NON ESS BUS
    1. Battery power can be restored to NON ESS BUS by placing the Normal/Recover switch to the RECOVER position
1. Prevents reverse current flow

### Standby Generator

1. Backup power for ESS No 1 BUS
1. 28V 7.5amp
1. When placed in standby a circuit is completed from the switch through the voltage regulator to the switch circuit of the relay to ensure its only connected when proper voltage is supplied

### Standby Voltage Regulator

1. Adjustable, Solid-state, linear regulator
1. Located on the equipment shelf above baggage compartment
1. Provides
    1. undervoltage
    1. overvoltage
    1. short-circuit protection
    1. proper system voltage

### External Power

Powers all three BUSES when connected

### Voltmeter/Loadmeter

1. Voltmeter indicates voltage for the power source or BUS selected with the voltmeter select switch
1. Loadmeter indicates, in percent, the main or standby generator output depending on the voltmeter selector switch

### Inverters

1. Take input of 28VDC and produce 400Hz 115V 26V AC

1. Avionics Inverter
    1. Avionics
    1. FCS yaw axis
1. FCS Inverter
    1. FCS only

Controlled by CBs, not switches
 - `AVIONICS INV`
 - `FCS`

## MINISTAB

Purpose is to provide basic IMC flight capability in the form of an FCS

The System consists of
 - 3 computers
 - 3 trim dampener units (TDU)
 - 1 Air Data Computer (ADC)
 - 3 actuators
 - 3 actuator position indicators
 - 1 MINISTAB controller
 - 1 junction box
 - 2 cyclic grip trim switches
 - 2 pedal trim micro-switches

### Controller

![Image][nfm-2-26]

### TDU

Primarily provide "trim" functions for the flight controls

Incorporates
 - magnetic brake
    - released when pressing the force trim cyclic button or setting the FT button on the FCS control to OFF
    - when FT is off control inputs are viscously damped by means of an Eddy Current Damper to prevent abrupt control inputs
 - force gradient springs
 - viscous dampeners
 - Control Motion Detector (CMD)
    - engages with the magnetic brake and detects when the cyclic is displaced from the "trimmed" position, sending a signal to the FCS of the corresponding axis

### Yaw FT

Incorporates
 - magnetic brake
 - force trim springs
 - pedal micro-switches

The magnetic brake and force trim springs are released when the FT button is set to OFF or when either set of both pedals are pressed simultaneously

### Control Tube/Actuator Assemblies





<!-- links -->

[systems-9-1]: https://github.com/wesleyem/th57/blob/master/images/systems-9-1.png?raw=true
[nfm-2-26]: https://github.com/wesleyem/th57/blob/master/images/nfm-2-26.png?raw=true


[c]: https://img.shields.io/badge/TH--57-C-orange.svg?style=flat-square
[b]: https://img.shields.io/badge/TH--57-B-blue.svg?style=flat-square
