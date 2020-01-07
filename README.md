# FDD_Modelica
## 1. Introduction
This repo is creating fault models in Modelica for DXCoils and Airloops. < br/ >
The fault models of DXCoils are based on the fault-free models in EnergyPlus.   < br/ >
Fault-free models for DXCoils are a set of performance curve equations, from the EnergyPlus Engineering Reference (Chapter 15.2.4, 15.2.5, 15.2.6, 15.2.7).  < br/ >
The fault models of DXCoils were developed by NREL technical report: FDD_Algorithms_PurdueU.pdf (in the attachment).  < br/ >
The fault models of DXCoils are available in OpenStudio Measure: *https://github.com/NREL/OpenStudio-fault-models/tree/master/fault_measures_2017.*   < br/ >
The airloop fault models are: OA-temperature-sensor fault, SA-temperature-sensor fault, and OA-damper stuck.  < br/ >


## 2. Fault Models of DXCoils available in OS-Measure (to be implemented in Modelica):
  * (1) condenser fouling
  * (2) non-standard charging
  * (3) condenser fan degradation
  * (4) presence of non-condensable in refrigerant
  * (5) liquid-line restriction
  * (6) evaporator fouling

## 3. Fault Models for AirLoops:
  * (1) biased OA temperature sensor
  * (2) biased SA temperature sensor
  * (3) OA-damper stuck

## 4. Fault Models currently not available, but worth exploring using Modelica:
  * (1) compressor valve leakage


