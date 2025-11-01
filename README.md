# BMW E30 Gauge Cluster Early Model
The goal for this project is to reverse engineer every PCB in the gauge cluster for early model year BMW E30's. This includes the main PCB referred to as the "Nexus" board and the smaller boards that are part of the tachometer and speedometer gauge assemblies. The SI (Service Interval) board has already been successfully reverse engineered and improved by Fabian Gmeiner. His project is linked below. 

## Fabian Gmeiner's SI board project:
https://github.com/FabianGmeiner/BMW_E30_SI_Board

# Progress
08/17/25
The Nexus board is the only board that has been started so far, the other project files are placeholders for now. The Nexus board is nearly complete but still needs to be touched up slightly before being sent off to a manufacturer. Things like via placements, and bulb footprints need to be adjusted as well as verifying the board cut hole locations via a laser cut version. -Ansel84

08/20/25
Begun laser cutting Nexus board tests to ensure that the layout will work before sending off gerbers to be made. Will work on other boards in the meantime. -Ansel84

08/25/25
Started on the speedometer board. Decoded the schematic and layout for the simple speedometer circuit (no O2 sensor indicator circuit). -Ansel84

08/26 - 29/25
Had to find other examples as the one I have only is part of the full circuit. Was able to figure out the circuit from pictures provided by a discord member. -Ansel84

08/30/25
Hall effect sensor PCB replicated. NOTE: if this is ever produced it is only compatible with the Speedometer PCB designed in this project, not compatible with the original board. -Ansel84

09/01/25
speedometer PCB schematic completed. -Ansel84

09/03/25
EG schematic completed. -Ansel84

10/20/25
First run of Nexus board PCB's arrived from JLCPCB. Unfortunately the Connector IV and connector V footprints are not compatible with the original connectors. Also, the fuel gauge location is not quite right, as well as a few lights and screw hole locations. Finally, J1 (Blue connector) location was slightly off. A second set of PCB's will be ordered hopefully fixing these issues. -Ansel84

10/30/25
Updated footprint library to include the coding plug switch and connectors to the EG board. Component locations are in place on this board now. NOTE: double check the locations of J1 and J2 to ensure they are exact, they are only approximate now. -Ansel84

11/01/25
Component locations are complete on the tachometer pcb layout. 

# Late Model Clusters:
If you have a late model cluster and need parts for that, check out the progress of the late model project here: https://github.com/Ansel84/BMW-E30-Gauge-Cluster-Late-Model
