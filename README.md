# SIRV Vaccination Simulation

This project simulates the spread of a contagious disease using a **Susceptible-Infected-Recovered-Vaccinated (SIRV) model**. It allows you to:

- Track the number of susceptible, infected, recovered, and vaccinated individuals over time.
- Estimate the minimum vaccination rate needed to suppress an outbreak.
- Visualize the epidemic as **dynamic plots and animations** showing how infections, recoveries, and vaccinations evolve day by day.

## Features

- Uses real population data from your local area.
- Implements vaccination as a control measure.
- Generates scatter plots and 2D grid visualizations for easy interpretation.
- Can analyze different vaccination strategies and their effects on peak infections.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- (Optional for animations) ffmpeg if running locally

## Usage

1. Load your population CSV:

```python
import pandas as pd
df = pd.read_csv('population.csv')

![Adequate vaccination rate](Recording2025-10-16141349-ezgif.com-optimize.gif)

![In-adequate vaccination rate](ezgif.com-optimize.gif)