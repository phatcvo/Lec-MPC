# Lectures - Model Predictive Control

This repository contains lectures and tutorials on Model Predictive Control (MPC) built with Quarto.

## 🌐 Website

The website is automatically deployed to GitHub Pages at: [https://phatcvo.github.io/Lec-MPC/](https://phatcvo.github.io/Lec-MPC/)

## 📚 Contents

- Introduction to Model Predictive Control
- Linear Model Predictive Control
- Nonlinear Model Predictive Control
- Iterative Linear Quadratic Regulator
- LPV Model Predictive Control for Racing
- MPC for Quadrotor Control
- And more...

## 🛠️ Development

This is a Quarto website project. To build locally:

```bash
# Install Quarto from https://quarto.org/docs/get-started/

# Clone the repository
git clone https://github.com/phatcvo/Lec-MPC.git
cd Lec-MPC

# Render the website
quarto render

# Preview locally
quarto preview
```

## 🚀 Deployment

The website is automatically built and deployed to GitHub Pages using GitHub Actions whenever changes are pushed to the `master` branch.

## 📝 Adding New Content

1. Create a new `.qmd` file in the `posts/` directory
2. Update `_quarto.yml` to add the new file to the sidebar navigation
3. Commit and push - the site will automatically rebuild

## 🔧 Requirements

- Python 3.x with Jupyter and IPython
- Quarto
- Required Python packages: matplotlib, numpy, pandas, seaborn, plotly
