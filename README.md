
# Context-Aware Alpha Extraction (CAAE) Strategy

Welcome to the repository for the **Context-Aware Alpha Extraction (CAAE) Strategy**—a cutting-edge quantitative investment approach. This project dynamically adjusts factor exposures (e.g., value, momentum, quality) based on market conditions, economic indicators, and sentiment.

## Objective

The goal of the CAAE strategy is to maximize alpha by adapting factor weights to changes in macroeconomic regimes, sentiment trends, and volatility levels. By integrating traditional financial factors with alternative data sources, the strategy aims to outperform static models through context-aware decision-making.

## Core Components

### 1. **Factor Data and Construction**
   - **Traditional Factors**: Value, momentum, quality, and size factors sourced from Compustat and CRSP.
   - **Macroeconomic Indicators**: Economic data such as interest rates, inflation, and VIX sourced from FRED and Yahoo Finance.

### 2. **Macro Regime Classification**
   - Uses machine learning models (e.g., Logistic Regression, XGBoost) to classify market regimes (bull, bear, high inflation) and adjust factor weights accordingly.

### 3. **Sentiment-Driven Momentum Adjustment**
   - Leverages sentiment analysis from Google Trends, Reddit, and news sources to dynamically adjust momentum exposure.

### 4. **Volatility Management**
   - Incorporates volatility data (e.g., VIX) to scale portfolio risk, dynamically adjusting rebalancing frequency.

### 5. **Sector-Specific Weighting**
   - Sector adjustments align with macroeconomic conditions, emphasizing defensive sectors like utilities in high-interest-rate environments.

## Implementation Steps

1. **Data Collection and Preprocessing**: Clean and prepare financial and macroeconomic data.
2. **Factor Scoring and Ranking**: Rank stocks based on factor scores.
3. **Dynamic Factor Weighting**: Adapt factor weights based on macro regime and sentiment analysis.
4. **Backtesting**: Evaluate the strategy's performance using key metrics (e.g., Sharpe ratio, annualized returns).
5. **Optimization and Sensitivity Testing**: Test sensitivity to trading costs and rebalancing frequencies.

## Expected Outcome

The CAAE strategy aims to deliver superior risk-adjusted returns by responding dynamically to shifts in economic, sentiment, and volatility conditions, offering a robust, modern solution for quantitative investing.

---

**Contributors**:  
- Gabriele Monti  
- Juan Herrera  
- Fernando Garcia de Llano  

For questions or feedback, feel free to reach out!
