# "Grabette"/"Gripette" Electronic Boards

This repository is part of the "Grabette" project (https://github.com/pollen-robotics/grabette). It gathers several small PCBs of Grabette/Gripette. 

## Grabette
Grapette is the data acquisition side.

<img src="./docs/CAB01194_wiring_of_grabette.png" alt="grabette wiring"  width="800"/>

It is based on a battery-powered Raspberry PI 4 plus a HAT (github.com/pollen-robotics/elec_RPI_Robot_HAT) to which a serie of sensing elements is added. Camera, Stereo Camera, angle sensors, IMU (included on the HAT) and a button + a LED as user interface.

 - angle_sensor

<img src="./elec_angle_sensor/docs/img/elec_angle_sensor.png" alt="3d view" width="200"/>

 - IMU (Not used)

<img src="./elec_IMU/docs/img/elec_IMU.png" alt="3d view" width="200"/>

 - HMI

<img src="./elec_HMI/docs/img/elec_HMI.png" alt="3d view" width="200"/>


## Gripette
Gripette is the actuator side. 

<img src="./docs/CAB01195_wiring_of_gripette.png" alt="gripette wiring"  width="800"/>

It also gathers data with the same Camera/Stereo Camera system and drive motors. The "under-HAT" electronic board is associated to a Raspberry PI zero 2W. It has a interface to the motors (now Feetech wiring). A Bulk-head board makes the mechanical interface with the arm that holds Gripette.

<img src="./elec_gripette_hub_and_dyn/docs/img/elec_gripette_hub_and_dyn.png" alt="3d view" width="400"/>

Bulk-head:

<img src="./elec_gripette_hub_and_dyn/Bulkhead_Adapters/elec_bulkhead_XT30_USB-C/docs/img/elec_bulkhead_XT30_USB-C.png" alt="3d view" width="200"/>



## Basically
 - Designed with KiCAD 9.
