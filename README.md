# Arbitrage-Detection-in-Options-Trading


**Team Members:** Shivam Jayeshkumar Mehta & Divyanshu Verma


## Summary

This project applies an unsupervised deep learning approach using an autoencoder to detect potential arbitrage opportunities in S&P 500 (SPX) options data. By analyzing options Greeks, implied volatility, and market metrics, the model identifies anomalies based on reconstruction errors, highlighting pricing discrepancies.


## Application Features

- Load and preprocess SPX options dataset (filter and normalize data).
- Define an autoencoder model to compress and reconstruct the data.
- Train the autoencoder with training and validation sets using EarlyStopping.
- Identify anomalies based on reconstruction errors.
- Visualize the reconstruction error distribution and highlight anomalies.
- Save identified anomalies to a CSV file for further analysis.
- Automate the conversion of large `.txt` datasets to `.csv` using a custom Python script (`convert.py`).

## Results and Visualizations

The project outputs the following:

- **Reconstruction Error Distribution**: A histogram displaying the reconstruction errors with the anomaly threshold highlighted.
- **Identified Anomalies**: A dataset of flagged anomalies that may represent potential arbitrage opportunities.
- **Anomaly Visualization**: A plot to compare the for profit and loss by running a strategy with and without the identified anomalies.


## Notes

This project improved my understanding of unsupervised deep learning, specifically autoencoders, and their application to financial data analysis. I also gained insights into preprocessing techniques, anomaly detection, and the importance of model evaluation.
