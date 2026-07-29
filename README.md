# Monte Carlo Pi Estimator

An interactive Python Jupyter Notebook hosted on Google Colab that estimates the value of $\pi$ using random sampling and visualizes the results.

## 🧮 How It Works

1. Imagine a square of side length $2$ with a unit circle ($r = 1$) inside it.
2. The area of the square is $4$ and the area of the circle is $\pi$.
3. The ratio of the circle's area to the square's area is:
   $$\frac{\text{Area of Circle}}{\text{Area of Square}} = \frac{\pi}{4}$$
4. By generating $N$ random points uniformly across the square and counting how many land inside the circle ($M$), we approximate:
   $$\pi \approx 4 \times \frac{M}{N}$$

## 🚀 Run directly in Google Colab


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nidssaikia/monte-carlo-pi-estimator/blob/main/monte_carlo_pi.ipynb)
