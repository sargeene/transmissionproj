# T-Proj
132KV - Single Line Diagram (ETAP Model)

README – Single Line Diagram (ETAP Model)

 #         Overview
This project contains a Single Line Diagram (SLD) developed in ETAP to represent the electrical power distribution network of an industrial facility. The diagram illustrates the main power sources, transformers, buses, protection devices, and major loads connected across different voltage levels.

#        Key Features of the SLD
#	  Power Sources
o	Two external power grids:
-	PowerGrid1: 1250 MVA, 132 kV interconnection.
-	PowerGrid2: 1600 MVA, 132 kV interconnection.
o	Connections modeled through transmission lines with defined lengths (6–7.89 miles) and conductor parameters.
#	  Main Buses & Voltage Levels
o	132 kV: Primary distribution buses (MainBusA, MainBusB).
o	13.8 kV: Secondary distribution via step-down transformers (BusA, BusC).
o	4.16 kV / 0.48 kV: Low-voltage distribution for motors, compressors, pumps, server racks, and lighting.
#	  Transformers
o	Multiple step-down transformers (T1–T6) with varying MVA capacities (2–90 MVA).
o	Tap changers, vector groups, and impedances are included in the ETAP model.
#	  Loads
o	Large motor drives (e.g., Crushers, Compressors, Distillation Unit).
o	Pumps (450–500 HP).
o	Server racks, lighting systems, and auxiliary loads.
#	  Cables & Capacitors
o	Medium-voltage and low-voltage feeder cables are modeled with lengths and impedance parameters.
o	Capacitor banks connected for power factor correction (e.g., C1, C2, C3, C4).
#	  Protection & Switching Devices
o	Circuit breakers (CBs) and disconnect switches are installed at each major bus and load point.
o	Bus tie breakers and sectionalizers included for system flexibility and redundancy.

#            Applications
This ETAP model is intended for:
•	Load Flow Analysis – Power flow, bus voltages, transformer loading.
•	Short Circuit Analysis – Fault current calculation for system protection design.
•	Motor Starting Studies – Evaluate starting impact of large motors (e.g., 3500 HP crushers).
•	Reliability & Contingency Analysis – Assess redundancy between grids and transformers.
•	Arc Flash Analysis – Safety compliance and PPE category determination.

#          File Information
•	File Name: SLD.png
•	Format: Single Line Diagram (ETAP-generated schematic export).
•	Software: ETAP (Electrical Transient Analyzer Program).



