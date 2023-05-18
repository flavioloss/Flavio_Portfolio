#### Contato
##### E-mail: flavioploss@gmail.com
##### Phone: +55 (27) 99299-1265
##### LinkedIn: [https://www.linkedin.com/in/flavio-loss/](https://www.linkedin.com/in/flavio-loss-b398a5181/)

## Data Mining the Water Table: Project Overview
### [GitHub Project Page](https://github.com/flavioloss/waterpump_challenge/blob/main/)
### This project is from the Machine Learning challenge hosted on Driven Data. You can find the challenge [here](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/page/23/). 
I ranked 903 out of 13,000 competitors.


#### What was developed:
- Estimator: I developed a multi-class classification model to predict the functionality of water pumps. The model achieved an accuracy score of 82.15%.
- Exploratory Data Analysis: I performed a thorough analysis of the data, visualizing distributions, relationships, and correlations between variables.
- Feature Engineering and Importance: Using random forest, I determined the importance of each feature for the estimator. I also engineered features to handle non-numerical data and utilized spatial features such as latitude and longitude.
- Multiple models: I experimented with various models, including Random Forests, Neural Networks, and CatBoost. CatBoost yielded the best accuracy score.

#### After modeling, I built a deployable application to identify the category of water pumps on a map visualization of Tanzania. I used the Plotly Python library for this purpose.
#### To build and maintain the application online, I utilized Streamlit and Streamlit Cloud.
##### [Deploy Project Page](https://github.com/flavioloss/waterpump_deploy)
![img-1](https://github.com/flavioloss/Flavio_Portfolio/blob/gh-pages/images/map_waterpump.jpeg?raw=true)



## Machine learning approaches to skin cancer diagnosis using NIR spectroscopy data of skin lesions
### This project is a scientific research developed by a partnership of UFES (Federal University of Espirito Santo) and PAD (UFES's Dermatological Assistance Program) to collect and classify skin cancer lesion spectra between cancer and non-cancer
### [GitHub Project Page](https://github.com/flavioloss/nir-spectrum-classification)

### What was developed:
- Data Collection: since 2020, a skin lesion databate has been assembled and annotated as a gold-standard dataset for cutaneous cancer classification, using a MicroNIR spectrometer on communities from the state of Espirito Santo, Brazil.
- Exploratory Data Analisys: Multiple methods were employed to analyze and understand the spectra. Techniques like t-SNE were utilized to reduce the dimensionality of the data and visualize the separation between samples in each class.
- Data Augmentation: To address the class imbalance problem, we experimented with SMOTE (Synthetic Minority Over-sampling Technique) and GANs (Generative Adversarial Networks) to create synthetic samples. 
- Feature Engineering: We performed feature engineering on the spectral data by dividing the spectrum into subsequences and calculating statistical features such as standard deviation and skewness for each subsequence.
- Modelling: We conducted cross-validation experiments using various algorithms, including PLS-DA, SVM, XGBoost, Catboost, LightGBM, and 1D Convolutional Neural Networks. The LightGBM model achieved the best performance with a balanced accuracy of 85%.

#### Currently, the project is being revised to be published as a Scientific paper.
![img-2](https://github.com/flavioloss/Flavio_Portfolio/blob/gh-pages/images/spectrum_binary.jpg?raw=true)
