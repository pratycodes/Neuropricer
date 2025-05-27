# Neural SDEs for Option Pricing

This project implements a Neural Stochastic Differential Equation (SDE) based model to price financial derivatives, comparing it to classical models like Black-Scholes, Heston, and SABR. It uses real market data, stochastic calculus, and deep learning (PyTorch + torchsde).

## Project Structure
- `baseline/`: Black-Scholes, Heston, SABR
- `models/`: Neural SDE architecture
- `sde_solver/`: SDE simulation engine
- `pricing/`: Monte Carlo and option pricing
- `data/`: Real-world option chains
- `notebooks/`: EDA, prototyping
- `report/`: Mathematical derivations (LaTeX)

## Installation
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
