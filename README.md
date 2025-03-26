# :speech_balloon: A Hybrid BiLSTM-SAM-TTT Model for Ultradeep Drilling Logging Data Reconstruction

# ABSTRACT
Well logging data play an indispensable role in oil and gas exploration and resource evaluation, serving as a critical bridge between seismic data and geological interpretation. During the acquisition of logging data in ultradeep wells, challenges such as wellbore instability, collapse, formation loss, and technical limitations of logging instruments often lead to missing or distorted data. Traditional reconstruction methods for well logging data, including empirical modeling and multivariate fitting, exhibit limitations in complex geological environments due to their reliance on subjective experience, low prediction efficiency, and poor adaptability to heterogeneous formations. This study proposes a novel well logging curve reconstruction model, named BiLSTM-SAM-TTT, which integrates Bidirectional Long Short-Term Memory networks (BiLSTM), Self-Attention Mechanism (SAM), and Test-Time Training (TTT) algorithms to overcome these challenges in ultradeep wells of the Tarim Basin. By incorporating geological stratification and depth information as prior knowledge during training, the model effectively captures the sequential relationships between geological characteristics and logging responses, thereby enhancing reconstruction accuracy. Comparative experiments with conventional methods (e.g., multivariate regression, LSTM, and BiLSTM-SAM) demonstrate that BiLSTM-SAM-TTT achieves the lowest error rates and highest reconstruction accuracy for resistivity, density, and compressional wave slowness curves. Moreover, it exhibits superior robustness and generalization capabilities in practical applications, particularly for the compressional wave slowness curves (DTC) reconstruction. Furthermore, the predictive interval analysis under different confidence levels demonstrates that the BiLSTM-SAM-TTT model exhibits high predictive reliability and can effectively capture the variation trends of well logging curves. The reconstruction model proposed in this research provides a novel approach and methodology for addressing missing logging data in ultradeep formations, offering significant theoretical and practical value. It shows promise in advancing ultradeep oil and gas exploration and development technologies, contributing to the efficient exploration and development of hydrocarbon resources.

# Installation
***conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia***

# Requirements
- [x] numpy
- [x] pandas
- [x] sklearn
- [x] matplotlib
      

## Data and Model Request  (Google Drive)
* **Url**: https://drive.google.com/drive/folders/1al2wD71XUC8O40ptx8pVk-sj427mvMTK?usp=drive_link
