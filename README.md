# Self-Driving Car Simulation

## Overview

This project simulates a self-driving car in a custom environment. It uses Kivy for the graphical interface and a simple Deep Q-Network (DQN) for the artificial intelligence. The car learns to navigate towards a goal while avoiding obstacles drawn on the screen.

## Features

- **Dynamic Obstacle Drawing**: Draw obstacles in real time using the mouse.
- **Self-Driving**: Utilizes a DQN for navigation.
- **Sensor Emulation**: Virtual sensors detect the car's surroundings.

## Technologies

- Python
- Kivy
- NumPy
- Matplotlib

## Getting Started

### Prerequisites

- Python 3.10
- Kivy
- NumPy
- Matplotlib

### Installation

1. Clone the repository:
  git clone https://github.com/jivankesan/SelfDrivingCar.git

2. Install required packages:
  pip install -r requirements.txt

## Usage

Run `map.py` to start the self-driving car simulation:
python main.py

markdown
Copy code

## Controls

- **Clear**: Clears the obstacles on the screen.
- **Save**: Saves the current state of the neural network.
- **Load**: Loads the last saved state of the neural network.



