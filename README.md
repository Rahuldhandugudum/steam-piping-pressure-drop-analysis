# Automated Steam Piping Pressure Drop Analysis
Excel-based automated pressure drop analysis of a steam piping system using piping geometry, flow conditions, pipe friction, and minor losses.
This project involves the analysis and automation of pressure drop calculations in a steam piping system using Microsoft Excel. The model uses piping information from an engineering isometric drawing along with operating conditions to calculate pressure losses across individual pipe segments and the overall piping route.

The Excel workbook automates the calculation of flow velocity, Reynolds number, friction factor, major pressure loss, minor pressure loss, cumulative pressure drop, and outlet pressure.

Input Parameters
Fluid: Steam
Inlet pressure: 11 kg/cm²(g)
Temperature: 320 °C
Mass flow rate: 5 tonnes/hour
Pipe outside diameter: 219.1 mm
Pipe wall thickness: 6.35 mm
Calculated internal diameter: 206.4 mm
Pipe lengths and routing: Based on the supplied piping isometric
Engineering Calculations

The workbook includes:

Pipe internal diameter calculation
Flow-rate conversion
Steam flow velocity
Reynolds number
Flow-regime identification
Darcy–Weisbach major pressure loss
Minor pressure losses using K-values
Cumulative pressure loss along the piping route
Outlet pressure calculation
Comparison of pressure losses between pipe sections
Minor Losses Considered

The model allows K-values to be assigned to individual fittings, including:

90° long-radius elbows
90° standard elbows
45° elbows
Tees
Gate valves
Other fittings where applicable
Excel Automation

The workbook is structured so that changing the input parameters automatically updates the downstream engineering calculations.
## Data used
- <a href="https://github.com/Rahuldhandugudum/steam-piping-pressure-drop-analysis/blob/main/Automated%20Steam%20Piping%20Pressure%20Drop%20Analysis.xlsx">view Excel Calculations</a>

The calculation flow is:

Input Data → Pipe Geometry → Flow Properties → Reynolds Number → Friction Factor → Major Loss + Minor Loss → Segment Pressure Drop → Cumulative Pressure → Final Pressure

Key Excel Features Used
Excel formulas
Absolute and relative cell references
Structured calculation tables
Conditional logic
Engineering calculations
## Piping Parameters used
- <a href="https://github.com/Rahuldhandugudum/steam-piping-pressure-drop-analysis/blob/main/Piping%20isometric%20sample.pdf">view piping</a>

Data organization
Charts/visualization
Automated calculation workflow
