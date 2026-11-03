<img width="1536" height="1024" alt="Designer (1)" src="https://github.com/user-attachments/assets/045bfa4d-0742-4e26-93fd-ffbf31fbb1a8" />

> **Note:** This README provides a concise overview of the project, methodology and key findings. For the complete analysis, including the literature review, econometric framework, statistical outputs, robustness checks and full discussion of results, please refer to the accompanying PDF report:
>
[Analysis of the Consequences of a Global Economy under Recent Events.pdf](Analysis%20of%20the%20Consequences%20of%20a%20Global%20Economy%20under%20Recent%20Events..pdf)

# Oil Price Shocks and the UK Economy

### Analysing the Consequences of Global Economic Events on Oil Markets and Macroeconomic Stability

This repository contains an empirical analysis of how global events and oil market disruptions affect key UK macroeconomic indicators.

Using time-series econometric methods, the project investigates the relationship between Brent crude oil prices, the FTSE 100, and the GBP/USD exchange rate during a period marked by geopolitical tensions, sanctions, financial instability, and shifts in global energy markets. 

---

## Research Question

> How sensitive is the UK economy to oil price shocks arising from major global events?

---

## Overview

Oil continues to play a central role in global economic activity. Supply disruptions, geopolitical conflicts, economic sanctions, and financial crises can all generate significant movements in oil prices, with implications for financial markets and broader economic performance. 

This study examines whether fluctuations in Brent crude oil prices transmit into:

- UK equity markets (FTSE 100)
- The GBP/USD exchange rate
- Wider measures of economic stability

The analysis focuses on significant global events between August 2021 and November 2023. 【1-f1adc0】

---

## Data

The analysis uses weekly data derived from:

- Brent Crude Oil Prices
- FTSE 100 Index
- GBP/USD Exchange Rate

Data was sourced from financial and energy market providers and transformed for time-series analysis. 【1-f1adc0】

---

## Methodology

The project applies several econometric techniques:

### Stationarity Testing
- Augmented Dickey-Fuller (ADF) Tests

### Time-Series Modelling
- Vector Autoregression (VAR)
- ARIMA Modelling

### Dynamic Analysis
- Granger Causality Testing
- Impulse Response Functions (IRF)

### Structural Change Detection
- Bai-Perron Unknown Break Tests
- Chow Tests
- Wald Tests

These methods allow the analysis of both short-run market responses and longer-term structural shifts. 

---

## Key Findings

### Oil Markets Significantly Influence UK Equities

VAR and Granger-causality analysis suggest a statistically significant relationship between Brent crude oil prices and the FTSE 100. Changes in oil prices were found to have predictive power for movements in UK equity markets. 
### Exchange Rate Effects Are More Limited

The relationship between Brent crude oil prices and the GBP/USD exchange rate was considerably weaker and generally lacked statistical significance. 

### Global Events Matter

Structural break testing identified significant changes associated with:

- The G7 price cap on Russian oil
- The collapse of Silicon Valley Bank
- Major global energy market developments

Several of these events produced measurable impacts on UK financial markets through oil-price channels. 

### Interconnected Markets Create Vulnerability

The results highlight the UK's exposure to external economic shocks and reinforce the importance of monitoring developments in global energy markets. 

---

## Example Techniques

The project includes:

- Data cleaning and transformation
- Time-series preparation
- Structural break detection
- Forecasting models
- Dynamic response analysis

Software implementation was carried out using Stata. 
---

## Selected Results

Key empirical findings include:

- Bidirectional Granger causality between Brent crude oil prices and the FTSE 100.
- Strong short-run equity market responses to oil price shocks.
- Evidence of significant structural breaks linked to major international events.
- Limited evidence of a strong oil-price effect on the GBP/USD exchange rate. 

---

## Abstract

This project investigates the transmission of oil price shocks to the UK economy during a period of heightened geopolitical and financial uncertainty. Using VAR, ARIMA, structural break analysis, and impulse response modelling, the study evaluates the relationship between Brent crude oil prices, equity markets, and currency movements. The findings indicate that oil-price volatility remains an important driver of UK financial market performance, highlighting the continuing relevance of energy markets in an increasingly interconnected global economy.

---

*"Global markets may be interconnected, but the channels through which shocks spread are neither uniform nor predictable. Understanding those channels remains critical for economic resilience."*
