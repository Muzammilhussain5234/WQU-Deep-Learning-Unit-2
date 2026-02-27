# Time Series Forecasting using RNN, GRU, and LSTM

## Project Overview
This project focuses on time series forecasting using Recurrent Neural Networks (RNNs). The models are trained on daily temperature data to predict future temperature values.

The project compares the performance of different deep learning architectures in capturing temporal dependencies in sequential data.

---

##  Models Implemented
The following architectures were implemented and evaluated:

- Vanilla RNN  
- GRU (Gated Recurrent Unit)  
- LSTM (Long Short-Term Memory)

---

##  Methodology

### Data Preparation
- Dataset consists of daily temperature recordings.
- Sliding window technique was used to create sequential training samples.

Different window sizes were tested:
- 7 Days  
- 12 Days  
- 14 Days  
- 30 Days  

Each window was used to predict the next day’s temperature.

---

##  Training Approach
- Models were trained using multiple hyperparameter configurations.
- Training, validation, and testing phases were performed.
- Performance was evaluated using regression error metrics.

---

## Results

- GRU and LSTM models captured temporal patterns more effectively than Vanilla RNN.
- Gated architectures performed better due to their ability to retain long-term dependencies.
- After hyperparameter tuning, **GRU achieved the best overall performance**.

Detailed graphs, metrics, and experiments are available inside the notebooks.

---

##  Technologies Used
- Python  
- TensorFlow / PyTorch (mention whichever you used)  
- NumPy  
- Pandas  
- Matplotlib / Seaborn  

---


