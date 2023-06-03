# Introduction

In this repository we share files connected to our article "Control Oriented Models Of Series Hybrid Electric Powertrain"

Authors: Piotr Kotuszewski, Paweł Kluk, Andrzej Ordys, Krzysztof Kukiełka and Payman Shakouri

# How to run simulations

Requirements: Matlab R2018b with Simulink

Libraries: Simulink, Simscape, Simscape Electrical, Simscape Driveline

# How to run simulation
1. Install all required libraries to Matlab R2018b with Simulink
2. Load variables from ./data.mat
3. Open Simulink model ControlOrientedModelsOfSeriesHybridElectricPowertrain.slx
4. Manipulate variables from:
a) Matlab workspace
b) submodels' parameters
c) set Drive Cycle Source as you want
5. Run Matlab simulation with Accelerator to enhance simulation speed
6. Simulation will end when EndPosition distance will be reached or time of simulation will end
