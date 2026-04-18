# Probability & Convergence: A Simulation Approach

Welcome to this interactive data science project! This repository explores foundational concepts in probability theory and statistics through highly optimized Python simulations. 

Instead of relying solely on theoretical equations, this project uses computational power to simulate random events hundreds of thousands of times, demonstrating how empirical data beautifully converges to mathematical truth.

## Project Overview

The core analysis is documented in an interactive Jupyter Notebook, divided into four main sections:

### 1. The Coin Flip Experiment (Empirical Approach)
A vectorized simulation of flipping a coin 10,000 times, repeated across 100,000 trials. We answer a specific statistical question: *What is the probability of getting more than 5,050 heads?* This section visualizes the distribution of outcomes using a histogram.

### 2. The Analytical Approach (Central Limit Theorem)
We verify our simulation mathematically. By applying the **Central Limit Theorem (CLT)** and calculating the Z-score (including continuity correction for discrete-to-continuous approximation), we find the exact theoretical probability and compare it to our empirical results.

### 3. The Law of Large Numbers (Convergence)
A dynamic visualization tracking the cumulative empirical probability over 100,000 simulations. It visually proves the **Law of Large Numbers (LLN)** by showing how the chaotic initial data smooths out and perfectly converges to the theoretical target line.

### 4. The Monty Hall Paradox
A high-performance simulation of the famous game show puzzle. It empirically proves why changing your door yields a ~66.6% win rate, while staying with your initial choice keeps you at ~33.3%, resolving one of the most counter-intuitive problems in probability.

## Technologies Used

* **Python 3**
* **NumPy:** Used for vectorized operations and binomial distribution simulations, reducing computation time from minutes to milliseconds.
* **SciPy:** Used for calculating cumulative distribution functions (CDF) and precise theoretical probabilities.
* **Matplotlib:** Used for generating histograms and logarithmic convergence charts.
* **Jupyter Notebook:** Used for Data Storytelling, blending markdown explanations with executable code.

## How to Run This Project

To run these simulations on your local machine, ensure you have Python installed along with the required libraries.

1. Clone this repository:
   ```bash
   git clone [https://github.com/Slimacik12/probability-and-convergence.git](https://github.com/Slimacik12/probability-and-convergence.git)
