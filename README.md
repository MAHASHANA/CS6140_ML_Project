# LSTM-Based Traffic Prediction and Multimodal Synthetic Data Generation

### 👋 Welcome to the Project Repository of Group 18!
This repository showcases our work for **CS6140 Machine Learning** at **Northeastern University**. Our project dives into real-time traffic prediction and synthetic data generation using advanced models like **LSTMs**, **TimeGAN**, and more.

---

## 📝 Project Overview
Traffic prediction is a cornerstone of modern urban planning and smart cities. In this project, we:
- Developed machine learning models to predict real-time traffic patterns using the **PeMS-BAY dataset**.
- Enhanced predictive models by training them on **synthetic traffic data** generated via cutting-edge techniques such as:
  - **TimeGAN** (Time-series Generative Adversarial Networks).
  - **GaussianCopula**.
  - **PARSynthesizer**.
- Evaluated synthetic data quality against original data using **PCA**, **Kolmogorov-Smirnov (KS) tests**, and statistical comparisons.

---

## 🚀 Key Highlights
1. **LSTM Models for Traffic Prediction**:
   - Designed and trained LSTM models with multiple configurations.
   - Achieved the best performance with:
     - Sequence Length: `6`
     - Optimizer: `Adam`
     - Epochs: `20`
     - Batch Size: `64`
     - **R² Score:** `0.64`.

2. **Bidirectional LSTM for Improved Temporal Capture**:
   - Implemented a bidirectional architecture to process data in both forward and backward directions.
   - Best Configuration: R² Score `0.662`.

3. **Synthetic Data Generation**:
   - **TimeGAN**: Captured temporal dependencies but showed room for optimization in PCA analysis.
   - **GaussianCopula**: Modeled distributions effectively but added variability.
   - **PARSynthesizer**: Demonstrated potential with its probabilistic auto-regressive approach.

4. **Evaluation Techniques**:
   - Applied k-fold cross-validation to assess model generalization.
   - Compared synthetic and original datasets through:
     - Mean and Standard Deviation plots.
     - PCA visualizations.
     - Kolmogorov-Smirnov (KS) Test.

