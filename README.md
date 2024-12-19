# Brownian Motion Simulation

This repository contains a Python script to simulate Brownian motion using elastic collisions among particles (balls) inside a container. The simulation models ideal gas behavior and demonstrates principles of energy and momentum conservation.

## Features

- **Elastic Collisions**: Particles undergo elastic collisions with each other and the container walls.
- **Energy Conservation**: Verifies conservation of kinetic energy.
- **Pressure Calculation**: Computes pressure based on particle-wall interactions.
- **Optional Animation**: Visualize the simulation in real-time.

## File Structure

- `BALL_FINAL_Optimized.py`: Python script implementing the simulation.

## Requirements

The script requires the following Python libraries:

- `numpy`
- `matplotlib`
- `scipy`
- `itertools`

Install them using pip if they are not already installed:
```bash
pip install numpy matplotlib scipy
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/nzakhir/brownian-motion-simulation.git
   cd brownian-motion-simulation
   ```

2. Run the simulation:
   ```bash
   python BALL_FINAL_Optimized.py
   ```

3. To visualize the simulation, ensure `animate=True` is set when calling the `run` method in the script.

## Example Output

- **Pressure**: The script calculates and displays the pressure exerted on the container walls.
- **Kinetic Energy Conservation**: Confirms whether kinetic energy is conserved in each frame.
- **Animation**: Shows particles moving and colliding in real-time.
