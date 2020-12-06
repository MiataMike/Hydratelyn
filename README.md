# Hydratelyn
This project is a soil moisture sensor that can be interfaced to a MyDAQ, or just about any DAQ with a voltage input

## Probe selection
Most soil probes are made from PCB material, with ENIG plating (at best), which corrodes over time due to electrolysis
Hydratelyn uses 2mm pencil leads as the probes, which won't rust. The resistance of the probes was measured around 15 Ohms
from end to end, which is insignificant relative to the resistance of the soil

## Soil resistance
To figure out what resistance range we're trying to measure, I placed 2 leads in my plants' soil while it was dry and checked with a multimeter. It read 30M, which is very high. After watering it dropped to 7k. 
