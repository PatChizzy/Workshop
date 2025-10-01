# Conference Workshop

**7th Conference of the Pan African Society for Agricultural Engineering (ANAFIDE-PASAE / Afro-AgEng)**,  
**Theme: Water Management for a Sustainable and Resilient Agriculture in Africa**  
📍 Morocco, 2025

---

## About

This repository hosts the training materials prepared for the **hands-on workshop** delivered during the conference. The sessions combine **Python programming, data analytics, and irrigation modeling** with real and simulated environmental datasets.

Participants learn how to:
- Explore and visualize climate and soil sensor data
- Compute **reference evapotranspiration (ET₀)** using FAO Penman–Monteith
- Estimate **crop water requirements (ETc)** with crop coefficients (Kc)
- Derive **irrigation needs** under different efficiencies
- Run **scenario simulations** (heatwave, rainfall, drought) to observe how decisions shift
- Build **introductory machine learning models** for predicting weather and soil variables
- Interpret results with clear and compelling visualizations

---

## Workshop Structure

1. **Python & Numerical Computing**
   - Introduction to Python, NumPy, Pandas
   - Working with tabular data and time series

2. **Environmental Applications**
   - Weather and soil datasets
   - ET₀ and ETc calculations
   - Irrigation demand estimation
   - Comparison of in-situ weather station data with ERA5 reanalysis data  

3. **Scenario Lab**
   - Interactive simulations for:
     - Heatwaves 🌡️  
     - Rainfall events 🌧️  
     - Droughts 🌵  

4. **Machine Learning Intro**
   - Predicting **air temperature** and **solar radiation**
   - Model comparison (Random Forest, Decision Tree, Linear Regression, SVR)

5. **Soil Water Analysis**
   - Van Genuchten soil parameters
   - Soil texture and water retention (θFC, θWP, PAW)

---

## Requirements

- Python 3.8+
- Jupyter Notebook / Google Colab
- Recommended libraries:
  - `numpy`, `pandas`, `matplotlib`
  - `scikit-learn`
  - `ipywidgets` # for interactivity
