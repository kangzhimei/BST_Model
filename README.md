# :speech_balloon: A Hybrid BiLSTM-SAM-TTT Model for Ultradeep Drilling Logging Data Reconstruction
>A novel approach for reconstructing well logging data in ultradeep wells using Bidirectional Long Short-Term Memory networks (BiLSTM), Self-Attention Mechanism (SAM), and Test-Time Training (TTT) algorithms.

## 📚 ABSTRACT
Well logging data is crucial for oil and gas exploration, but data acquisition in ultradeep wells often faces challenges like wellbore instability and technical limitations. Traditional reconstruction methods show limitations in complex geological environments. Our BiLSTM-SAM-TTT model addresses these challenges by:

- Integrating BiLSTM, SAM, and TTT algorithms
- Incorporating geological stratification and depth information
- Enhancing reconstruction accuracy for ultradeep wells in the Tarim Basin

## 🌟 Key Features

- **Bidirectional LSTM**: Captures sequential relationships between geological characteristics
- **Self-Attention Mechanism**: Enhances feature learning capabilities
- **Test-Time Training**: Improves model adaptability during testing
- **Prior Knowledge Integration**: Uses geological stratification and depth information
- **Superior Performance**: Achieves lowest error rates in curve reconstruction

## 📊 Performance Metrics
The model demonstrates superior performance in reconstructing:

* Resistivity curves
* Density curves
* Compressional wave slowness curves (DTC)

# 🚀 Getting Started

## Installation
***conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia***

## Requirements
- [x] numpy
- [x] pandas
- [x] sklearn
- [x] matplotlib
      
## Data and Model Request  (Google Drive)
* **Url**: https://drive.google.com/drive/folders/1al2wD71XUC8O40ptx8pVk-sj427mvMTK?usp=drive_link

## Project Structure
```plaintext
BST_Model/
├── code/
│   ├── test.ipynb
│   ├── train.ipynb     
├── data/
│   ├── raw_data.csv
│   └── Test data set.csv
└── model/
    ├── model_DTC.pkl
    ├── feature_scaler_DTC.pkl
    ├── target_scaler_DTC.pkl
    └── onehot_encoder_DTC.pkl
```
## Training Process
1. **Data Preprocessing**
   > Process your `raw_data.csv` file according to your project requirements
   ```python
   # Example preprocessing steps
   - Handle missing values
   - Remove outliers
   - Normalize data
   - Feature engineering

2. **Update file paths in config**
   file_path = 'path/to/your/raw_data.csv'
   ```python
   # Model hyperparameters
   - hidden_dim1 
   - hidden_dim1 
   - hidden_dim1 
   - epochs 
   - learning_rate
   
4. **Run Training**


