# TR2-Vanguard

![TR-2 Vanguard Vehicle](docs/img/TR-2-Vanguard.png)

Technical Design Report (Phase A) and engineering assets for the TR-2 "Vanguard" SRLV mission. Features Industrial Reliability Doctrine, Rust-based safety-critical avionics, TubeSat payload integration, and Non-Euclidean recovery systems.

## Mission Specifications

![Vanguard Specs](docs/img/TR-2-Vanguard-4-Specs.png)

## Project Structure

The repository is organized as follows:

- **docs/**: Contains the Technical Design Report.
  - `TR-2-Vanguard.tex`: Main LaTeX source file.
  - `TR-2-Vanguard.pdf`: Compiled report.
  - `img/`: Images and figures used in the report.

- **simulations/**: Engineering simulations and data.
  - `openrocket/`: Flight simulations using OpenRocket (`.ork` files).
  - `motors/`: Solid rocket motor characterization and design files (`.eng`, `.ric`) for OpenMotor.

## Gallery

### Vehicle Views
<p float="left">
  <img src="docs/img/TR-2-Vanguard-2.png" width="45%" />
  <img src="docs/img/TR-2-Vanguard-3.png" width="45%" /> 
</p>

### Propulsion
![Trinity Motor](docs/img/trinity.png)

## Tools Required

- **LaTeX**: For compiling the documentation.
- **OpenRocket**: For flight path and stability analysis.
- **OpenMotor**: For internal ballistics simulation.
