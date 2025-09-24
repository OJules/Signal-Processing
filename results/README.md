# 📊 Results Directory - Signal Processing Analysis

This directory contains outputs from the signal processing analysis of historical time series data.

## 📁 Contents

### **Frequency Domain Analysis**
- `power_spectral_density.png` - PSD plots showing frequency content
- `fft_analysis.png` - Fast Fourier Transform results
- `spectrogram.png` - Time-frequency representation
- `frequency_characteristics.csv` - Dominant frequencies and amplitudes

### **Digital Filtering Results**
- `filter_design.png` - Filter frequency response plots
- `filtered_signals_comparison.png` - Before/after filtering visualization
- `noise_reduction_analysis.csv` - SNR improvement metrics
- `filter_parameters.json` - Optimal filter coefficients

### **Time Series Decomposition**
- `trend_analysis.png` - Long-term trend extraction
- `seasonal_components.png` - Seasonal pattern identification
- `residual_analysis.png` - Noise component characterization
- `decomposition_metrics.csv` - Component variance analysis

### **Statistical Signal Analysis**
- `autocorrelation_function.png` - Signal self-similarity analysis
- `cross_correlation.png` - Signal relationships (if multiple signals)
- `stationarity_tests.csv` - Statistical stationarity assessment
- `signal_statistics.json` - Mean, variance, higher-order moments

### **Performance Metrics**
- `processing_efficiency.csv` - Algorithm performance measurements
- `signal_quality_metrics.json` - SNR, THD, and other quality indicators
- `validation_results.txt` - Method validation against theoretical expectations

## 🎯 How to Generate Results

Run the signal processing notebook to populate this directory:
```bash
jupyter notebook Projet_SignalProcessing_JulesOdje.ipynb
```

The analysis workflow:
1. **Data Loading** - Historical data preprocessing
2. **Time Domain Analysis** - Basic signal characteristics
3. **Frequency Analysis** - Spectral content examination
4. **Filtering Application** - Noise reduction and enhancement
5. **Statistical Validation** - Performance assessment

## 📈 Key Signal Processing Indicators

Expected outputs include:
- **Dominant Frequencies** - Primary spectral components
- **Signal-to-Noise Ratio** - Quality improvement metrics
- **Filter Effectiveness** - Noise reduction performance
- **Trend Characteristics** - Long-term pattern analysis

---

*Note: Results demonstrate signal processing techniques applied to real historical data.*
