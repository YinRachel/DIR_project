# Time Series Forecasting

## Purpose of this Section
This section reviews time series forecasting methods commonly used in infrastructure resilience applications. Forecasting supports early warning, anomaly detection, capacity planning, and proactive intervention across water, power, transport, and other critical infrastructure systems.

The methods are organised by input structure and modelling paradigm, reflecting increasing levels of data complexity and generalisation capability.


---

## 1. Univariate Time Series Forecasting

### 1.1 Definition
Univariate forecasting models predict future values of a single time series using only its own historical observations.

### 2.2 Representative Models
- Persist
- Seasonal Persist

---

## 2. Multivariate Time Series Forecasting

### 2.1 Definition
Multivariate forecasting models output the same dimension as input feature


### 2.2 Representative Models
- Crossformer  
- ModernTCN  
- PatchTST  
- DLinear  
- iTransformer  
- TimeXer  

---

## 3. Multivariable Time Series Forecasting

### 3.1 Definition
Multivariable forecasting models only predict one target variable, with both target variable and exogenous variables as input


### 3.2 Representative Models
- DeformTime  
- Sonnet  


---

## 4. Time Series Foundation Models

### 4.1 Definition
Time series foundation models are large-scale models trained on diverse datasets to learn general temporal representations that can be transferred across tasks, datasets, and domains.



### 4.2 Representative Models
- MOMENT  
- MORIAI  
- Chronos  
- TimesNet  

### 4.3 Characteristics
- Zero-shot and few-shot forecasting capability
- Strong generalisation potential
- Higher computational and data requirements
- Evaluation must consider robustness and failure modes

---

## Comparison Across Forecasting Paradigms

| Paradigm | Input Structure | Strengths | Limitations |
|--------|----------------|-----------|-------------|
| Univariate | Single series | Simple, interpretable | No system interaction |
| Multivariate | Multiple correlated series | Captures dependencies | Sensitive to noise |
| Multivariable | Heterogeneous variables | Context-aware | Complex preprocessing |
| Foundation models | Large-scale, cross-domain | Strong generalisation | High resource cost |