# Poker Monte Carlo Simulator

**Author:** Will Tallard  
**Date:** December 2025  

## Overview
This Jupyter notebook simulates head-to-head poker equity between two starting hands using Monte Carlo simulations. Thousands of random board deals are generated to estimate win, loss, and tie probabilities.

## Features
- Accepts Hero and Villain hands (space or no space, uppercase/lowercase)
- Optional number of simulations for adjustable precision
- Validates input and prevents duplicate cards
- Displays results in a clean, easy-to-read format
- Progress bar shows simulation progress

## Dependencies
- Python 3.x
- `phevaluator`
- `tqdm` (for progress bar)

Install dependencies with:

```bash
pip install phevaluator tqdm
