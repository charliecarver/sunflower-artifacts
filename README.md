# Sunflower Artifacts
This is a collection of public artifacts for our paper, "Sunflower: Locating Underwater Robots From the Air," appearing in MobiSys 2022. Each file is a simulation used to guide/verify our choices for our communication, sensing, and laser scanning designs. If there are any questions on using the simulations, please [reach out to me directly](http://charliecarver.me).

## Directory Listing
- `/simulations/`
	- `connection-time/connection_time.m`: Computes percentage of hit/miss given a diverging laser beam and water wave
	- `fsk/fsk_demodulation.m`: Encoding/decoding of FSK with sync frequency 
	- `mems-scanning/mems_scanning.m`: MEMS mirror scanning trajectories
	- `param-tuning/param_tuning.m`: Parameter tuning for optimizing sensing distance
	- `scanning-pattern/scanning_pattern.m`: Modified Archimedean spiral simulator
	- `scanning-coverage/simulation_spiral_v1.m`: Simulate the underwater scanning pattern coverage influenced by the water waves

## Usage
- `.m` files can be opened, analyzed, and ran in MATLAB. All required code should be included, although additional MATLAB packages may need to be installed.
