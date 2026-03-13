# Taylor Series Visualisations

Interactive explorations of Taylor polynomial approximations — watch them converge within the radius and diverge beyond it.

### [Launch App](https://brendanjameslynskey.github.io/Taylor_Series_Visualisation/)

---

## What is this?

A single-page interactive tool for visualising how Taylor series approximate functions. Select from 20 functions, adjust the polynomial order with a slider, and see the approximation evolve in real time.

The shaded region on each plot marks the **radius of convergence** — inside it the polynomials converge to the true function; outside, they diverge, often dramatically.

## Functions

| Category | Functions |
|----------|-----------|
| **Algebraic** | 1/(1-x), sqrt(1+x), (1+x)^(1/3), 1/sqrt(1-x) |
| **Logarithmic** | ln(1+x), arctanh(x) |
| **Trigonometric** | sin(x), cos(x), tan(x), arctan(x), arcsin(x), sec(x) |
| **Hyperbolic** | tanh(x), sinh(x) |
| **Exponential** | e^x, e^(-x^2) |
| **Special** | sin(x)/x, erf(x), x/(e^x - 1) |
| **Rational** | 1/(1+x^2) |

## Features

- **20 functions** with their Taylor series, each with mathematical context
- **Adjustable polynomial order** (1 to 30) via slider
- **Convergence region shading** with dashed boundary lines
- **Multiple approximation orders** displayed simultaneously for comparison
- **Singularity markers** shown as dotted vertical lines
- **Pan, zoom, and scroll** on all plots (Plotly.js)
- **Dark theme** UI, fully responsive

## Built with

- [Plotly.js](https://plotly.com/javascript/) for interactive plotting
- Vanilla HTML/CSS/JS — no build step, no dependencies to install
