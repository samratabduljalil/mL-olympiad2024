# ML Olympiad - CO2 Emissions Prediction Challenge 🌍

The **CO2 Emissions Prediction Challenge** focuses on addressing the global issue of **carbon dioxide (CO2) emissions** and their environmental impact. As part of the **#MLOlympiad**, this competition encourages participants to leverage **machine learning techniques** to forecast **CO2 emissions per capita for the year 2030**, contributing to climate action and sustainability efforts.

---

## Challenge Overview

### Dataset  
The dataset spans **2000 to 2020** and includes a variety of **socio-economic and environmental indicators** from multiple countries, such as:  
- **Access to Electricity**  
- **Agricultural Land Usage**  
- **Energy Consumption**  
- **Population Growth**  
- **GDP per Capita**  
- **Other Environmental Factors**

### Objective 🎯  
Participants were tasked with building **predictive models** to accurately forecast CO2 emissions per capita for **2030**. The insights aim to support policymakers, businesses, and communities in reducing greenhouse gas emissions and promoting sustainability.

---

## Models Used

Various models were explored, with a focus on balancing **statistical methods** and **machine learning techniques**:  

1. **Long Short-Term Memory (LSTM)**  
   - Effective in capturing sequential patterns for time-series predictions.  

2. **ARIMA (Auto-Regressive Integrated Moving Average)**  
   - Models trends and seasonality for structured time-series data.  

3. **SARIMA (Seasonal ARIMA)**  
   - Extends ARIMA by incorporating seasonal effects.  

4. **Logistic Regression**  
   - Provides a straightforward baseline model for predictions.  

5. **Facebook Prophet**  
   - Handles trends and irregularities in time-series data.

### Best Performing Model: **Combination of ARIMA + Logistic Regression + LSTM**  
The combination leveraged the strengths of each method:  
- **ARIMA** captured temporal trends.  
- **Logistic Regression** identified linear relationships.  
- **LSTM** handled sequential and non-linear patterns.

---

## Key Hyperparameters

Fine-tuning hyperparameters played a critical role in achieving optimal results. The key parameters included:  
- **Learning Rate**: Experimented with values like `0.001`, `0.005`, and `0.01`.  
- **Warm-Up Iterations**: Stabilized training with `1000 warm-up iterations`.  
- **Max Iterations**: Set at `12000` for complete model training.  
- **Batch Size**: Adjusted between `8`, `16`, and `32` for balance between performance and memory usage.  

---

## Results

- The **ARIMA + Logistic Regression + LSTM** combination provided the best performance with the lowest **Mean Absolute Error (MAE)** and **Root Mean Square Error (RMSE)**.  
- Data preprocessing and augmentation significantly improved model accuracy.  

---

## Repository Structure

The repository is organized as follows:

