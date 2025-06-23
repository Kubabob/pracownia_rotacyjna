![Python](https://img.shields.io/badge/Python-3.10-blue)
![NumPy](https://img.shields.io/badge/NumPy-1.24.0-green)
![SciPy](https://img.shields.io/badge/SciPy-1.11.0-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7.0-red)
![Jupyter](https://img.shields.io/badge/Jupyter-6.5.0-purple)

This repository contains computational physics simulations focusing on quantum systems, specifically analyzing entropy and the effects of different pulse types on atomic excitation. The project demonstrates the application of numerical methods to quantum physics problems and includes comprehensive visualizations.

## Project Overview

This project investigates two key aspects of quantum systems:

1. **Quantum Entropy Calculations** - Analysis of entropy in quantum systems under different conditions
2. **Pulse Type Analysis** - Examination of how different pulse types affect atomic excitation probability

## Content

The project includes:
- **Jupyter Notebooks**:
  - entropia.ipynb - Entropy calculations and visualization
  - `impulsy.ipynb` - Simulation of pulse effects on atomic systems

- **Comprehensive Report**:
  - `sprawozdanie.pdf` - Detailed findings and theoretical background
  - sprawozdanie.tex - LaTeX source for the report

- **Visualizations** in the `graphics` folder, organized by:
  - `entropia/` - Entropy visualization for different pulse types
  - `impulsy/` - Pulse shape visualizations
  - `Pe/` - Probability analysis for different pulse types
  - `Pe_omega/` - Frequency domain analysis

## Analysis Process

### Pulse Type Implementation
- Rectangular pulse simulation
- Rising exponential pulse simulation
- Falling exponential pulse simulation
- Gaussian pulse simulation

### Probability Calculations
- Time evolution of atomic excitation probability
- Maximum excitation probability analysis
- Frequency domain response analysis

### Entropy Analysis
- Entropy calculations for different pulse types
- Quantum entanglement considerations
- Time-dependent entropy evolution

## Key Findings

- Demonstrated how different pulse shapes affect atomic excitation probability
- Analyzed the relationship between pulse parameters and excitation efficiency
- Calculated entropy measures for various quantum states
- Explored quantum entanglement detection and limitations

## Folder Structure

```
├── entropia.ipynb           # Entropy calculations notebook
├── impulsy.ipynb            # Pulse analysis notebook
├── sprawozdanie.pdf         # Compiled report
├── sprawozdanie.tex         # LaTeX source of the report
├── sprawozdanie/            # Report files
│   ├── sprawozdanie.pdf     # Compiled report
│   ├── sprawozdanie.tex     # LaTeX source of the report
├── graphics/                # Visualization files
│   ├── entropia/            # Entropy visualizations
│   ├── impulsy/             # Pulse type visualizations
│   ├── Pe/                  # Probability visualizations
│   └── Pe_omega/            # Frequency domain visualizations
```

## Technologies Used

- **Python** - Primary programming language
- **NumPy** - Numerical computations
- **SciPy** - Scientific computing and integration
- **Matplotlib** - Data visualization
- **Jupyter Notebooks** - Interactive development and analysis
- **LaTeX** - Scientific report preparation

## Visualizations

The project includes visualizations of:
- Different pulse types (rectangular, exponential rising/falling, Gaussian)
- Excitation probability over time for each pulse type
- Maximum excitation probability vs. frequency
- Entropy evolution for different quantum states

## How to Run

1. Clone this repository
2. Install required dependencies: `uv sync`
3. Open the Jupyter notebooks: `jupyter notebook entropia.ipynb` or `jupyter notebook impulsy.ipynb`

## License

This project is available under the MIT License.

## Acknowledgments

Special thanks to Dr. Anita Dąbrowska for her guidance on this laboratory project.