*This repository includes three explanatory .txt files that describe the core codes developed for my Ph.D. dissertation on multi-layer soil moisture (SM) estimation, forecasting, and downscaling using deep learning. Each file corresponds to one dissertation chapter:*

**Chapter 1 – Soil Moisture Estimation**
The first file explains the ConvLSTM framework used to estimate daily multi-layer SM across the continental United States. It details data preprocessing, input predictors (e.g., SMAP, NLDAS-2, MODIS, soil properties), and model training steps for generating layer-specific SM estimates.

**Chapter 2 – Soil Moisture Forecasting**
The second file describes a ConvLSTM framework applied for SM nowcasting and forecasting at different lead times (1-, 3-, 7-, 14-, and 30-days ahead). For same-day estimation, the forecasting horizon is set to zero. For forecasting, this value is adjusted to the desired lead time. The documentation highlights how the methodology remains consistent with Chapter 1, but extends to short- and mid-term prediction tasks.

**Chapter 3 – Soil Moisture Downscaling**
The third file documents the CNN-LSTM framework designed to downscale SMAP soil moisture products from 9 km to 100 m resolution. It explains data preparation, model architecture, and evaluation against dense monitoring networks, demonstrating improved performance in capturing local-scale soil moisture variability.

Together, these files provide detailed explanations of how the models were built, trained, and applied, supporting reproducibility and enabling further research applications.
