# Interest Rate Risk and Bond Pricing

A comprehensive analysis of interest rate risk modeling and bond pricing using the Dothan interest rate model.

## Overview

This project explores:
- **Dothan Interest Rate Model** - Stochastic modeling of interest rate paths
- **Bond Pricing** - Pricing bonds under stochastic interest rates
- **Risk Analysis** - Portfolio risk assessment and duration analysis
- **Simulation** - Monte Carlo simulation of interest rate scenarios

## Project Structure

- `index.qmd` - Home page
- `introduction.qmd` - Project introduction
- `objectives.qmd` - Project objectives
- `dothan-model.qmd` - Dothan model theory and implementation
- `simulation.qmd` - Interest rate path simulations
- `bond-pricing.qmd` - Bond pricing methodology
- `bond-pricing-estimation.qmd` - Detailed pricing calculations
- `graphical-analysis.qmd` - Comprehensive visualizations
- `risk-analysis.qmd` - Portfolio risk analysis
- `deliverables.qmd` - Project deliverables summary
- `about-us.qmd` - About the project

## Building the Project

### Prerequisites
- [Quarto](https://quarto.org/docs/get-started/) (version 1.3 or later)
- Python 3.8+
- Required Python packages: `matplotlib`, `numpy`, `scipy`, `pandas`

### Local Build

```bash
# Install dependencies
pip install matplotlib numpy scipy pandas

# Render the project
quarto render

# Preview the project
quarto preview
```

## Deployment

This project is automatically deployed to GitHub Pages using GitHub Actions. 

To view the live website, visit: `https://Korngmeng-Taing.github.io/Interest-rate/`

### Manual Deployment

If you need to manually update GitHub Pages:

```bash
# Render locally
quarto render

# Push _output folder to gh-pages branch
quarto publish gh-pages
```

## Contact

For questions or feedback about this project, please contact the project team.
