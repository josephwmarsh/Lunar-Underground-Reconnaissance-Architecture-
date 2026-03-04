# Lunar-Underground-Reconnaissance-Architecture-
Comprehensive mission architecture for a lunar reconnaissance expedition, featuring orbital trajectory modeling (Hohmann Transfer), power system trade studies, and communication relay link budgets.

## Mission Overview
The Lunar Underground Reconnaissance Expedition (LURE) is a comprehensive systems architecture designed to deploy a dual-asset payload, an Orbital Relay Satellite and a Surface Rover, to the Moon. The mission utilizes a SpaceX Falcon 9 launch vehicle to transport the 1,310.8 kg integrated payload to a stable lunar environment for the purpose of mapping sub-surface lava tubes and assessing habitation viability.

## Technical Specifications and Core Contributions
As a key contributor to the Systems Architecture and Orbital Dynamics, my work involved the mathematical validation of the mission trajectory, propulsion trade studies, and communication link persistence.

### Orbital Mechanics and Trajectory Validation
* **Mission Profile:** Executed a trajectory plan starting from a 500 km Low Earth Orbit (LEO) with a Hohmann Transfer to a 1,000 km Low Lunar Orbit (LLO).
* **Delta-V Budget:** Validated a total mission Delta-V of approximately 3.94 km/s, including:
    * **Trans-Lunar Injection (TLI):** 3.12 km/s
    * **Lunar Orbit Insertion (LOI):** 0.82 km/s
* **Retrograde Capture:** Calculated the necessary burn parameters using the Patched Conics method to ensure precise capture into the target 1,000 km lunar altitude.

### Propulsion and Power Systems Architecture
* **Orbiter Propulsion:** Selected a Bi-Propellant system (Monomethelhydrazine/Nitrogen Tetroxide) for the satellite, optimizing for a Specific Impulse (Isp) of 315s to handle high-mass orbital maneuvers.
* **Rover Descent:** Implemented a Nitrogen Cold Gas system for the rover's controlled descent to the lunar surface.
* **Power Management:** * **Rover:** Integrated a Multi-Mission Radioisotope Thermoelectric Generator (MMRTG) providing 110W (Beginning of Life) to ensure survival through the 14-day lunar night.
    * **Orbiter:** Designed a 12.33 square meter solar array yielding 1,850W to power high-gain communication relays.

### Communication and Data Relay
* **Dual-Band Link Architecture:** Orchestrated a tiered communication strategy:
    * **Proximity Link:** X-Band frequency for high-speed data transfer between the Rover and the Satellite.
    * **Earth Link:** S-Band frequency for long-range data transmission from the Satellite to the NASA Deep Space Network (DSN).

## Systems Engineering and Analysis
* **Mass Properties:** Managed a strict mass budget, resulting in a 483.0 kg Surface Rover and an 827.8 kg Orbital Satellite (Wet Mass).
* **Thermal Mitigation:** Validated the use of Multi-Layer Insulation (MLI) and specialized radiators to maintain a 20C internal operating temperature for avionics against a -173C to 127C external environment.
* **Trade Studies:** Authored the critical comparisons for propellant selection (Bi-propellant vs. Monopropellant) and power generation (RTG vs. Solar/Battery).

## Repository Contents
* **LURE_Architectural_Report.pdf**: Complete technical documentation of the LURE mission architecture, including mission timelines, subsystem breakdowns, and risk mitigation strategies.

  
## Contributors
* **Joseph Marsh** - Systems Architecture and Orbital Dynamics
* James Stanley
* August Tam
* Saegis Abbott
* Maxfield Young
