# Race Strategy Optimization using Monte Carlo Simulations

This project utilizes Monte Carlo simulations to optimize race strategies for motorsport events. It supports both serial and parallel computations, enabling efficient analysis of race scenarios. The program compares various pit stop strategies, tire usage plans, and their impact on race times, tire degradation, and fuel usage.

## Features
- **Simulation Options:** Choose strategies like One Stop, Two Stop, Three Stop, or No Stop.
- **Parallel Processing:** Leverages multiple CPU cores for improved performance.
- **Data Analysis:** Provides metrics for race times, tire degradation, and fuel consumption.
- **Visualizations:** Generate comparison plots for serial and parallel results.
- **Flexible Input:** Accepts inputs through keyboard prompts (CSV support under development).

## Installation
### Prerequisites
- Python 3.8 or higher
- Required Python libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `prettytable`
  - `concurrent.futures`

Install the dependencies using the following command:
```bash
pip install numpy pandas matplotlib prettytable
```

## Usage
1. Clone this repository or download the Python script:
   ```bash
   git clone https://github.com/your_username/race-strategy-optimizer.git
   cd race-strategy-optimizer
   ```
2. Run the program:
   ```bash
   python race_strategy_optimization_using_monte_carlo_simulations.py
   ```

3. Select input method when prompted:
   - Enter race strategy details through the keyboard.

4. Review the simulation results displayed in the terminal and visualizations generated.

## Key Input Parameters
- **Strategy:** Race strategy (e.g., "Two Stop").
- **Tire Sequence:** Tire sequence (e.g., "Soft-Soft-Med").
- **Baseline Lap Time:** Estimated average lap time in seconds.
- **Total Race Laps:** Total number of laps for the race.
- **Pit Stop Time Loss:** Time penalty for each pit stop in seconds.

## Example Input
```
Strategy: Two Stop
Tire Sequence: Soft-Medium
Baseline Lap Time: 95.5
Total Race Laps: 60
Pit Stop Time Loss: 22.5
```

## Outputs
- **Race Time Analysis:** Comparison of serial and parallel race times.
- **Performance Metrics:** Speedup and efficiency of parallel processing.
- **Visualizations:** Histograms and bar plots for in-depth insights.

## Future Work
- Add CSV input functionality.
- Implement advanced pit stop strategies and scenarios.
- Extend visualizations to include additional performance metrics.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
Special thanks to the Python and data science communities for providing robust libraries that make projects like this possible.
