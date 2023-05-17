# TLIA: Time-Series Forecasting Model using Long Short-Term Memory Integrated with Artificial Neural Networks for Volatile Energy Markets
This is the primary code for the article titled "TLIA: Time-Series Forecasting Model Using Long Short-Term Memory Integrated with Artificial Neural Networks for Volatile Energy Markets" published [here](https://www.sciencedirect.com/science/article/pii/S0306261923005949) in the Applied Energy Journal.
>
## Abstract
Due to weather and political fluctuations that significantly impact the production and price of energy sources, enhancing data distribution and reducing data complexity is crucial to achieving accurate forecasting. Additionally, it is essential to provide a flexible forecasting model capable of handling rapid changes in the energy market and effectively anticipating energy supplies and demands. This study introduces a novel method to deal with energy market fluctuations in the long and short term and provide highly accurate forecasts for various energy data. It uses the Enhancing Transformation Reduction (ETR) method to improve the stationarity of the data, reduce seasonality and trend, and resolve rapid fluctuations. The output of ETR is then passed into a hybrid forecasting model referred to as “ Time-Series Forecasting Model using Long Short-Term Memory integrated with Artificial Neural Networks” (TLIA). The TLIA model benefits from transfer learning, which transmits the output of the LSTM layers into the ANN layers, enabling TLIA to base its work on the best performance and continue improving it. The study evaluates and tests its methods using six different datasets, including the electricity dataset of Victoria State, the oil price for the West Texas Intermediate, the Elia Grid load dataset, and wind power production. In addition to its characteristics, ETR accelerates and enhances the TLIA processing to achieve the highest accuracy compared to seven forecasting models in all six datasets. The TLIA is often 40 times or more superior to competing models. Compared to another model, the Mean Absolute Error (MAE) results of TLIA range between (0.008 and 0.088) versus (0.77 and 4318.544).
>
**Code Operation Requirements:**
- Python Version: 3.9.16
- Tensorflow Version: 2.12.0
- Numpy Version: 1.22.4

**Datasets that have been used in the study can be downloaded from the following links:**

1. https://www.kaggle.com/datasets/aramacus/electricity-demand-in-victoria-australia
2. https://www.kaggle.com/datasets/sc231997/crude-oil-price
3. https://opendata.elia.be

### The processing steps of the study.
![alt text](https://github.com/DalalAL-Alimi/TLIA/blob/main/images/2.PNG)

### The structure of the TLIA model.
![alt text](https://github.com/DalalAL-Alimi/TLIA/blob/main/images/TLIA.PNG)

###  The actual and ETR values for the six datasets.
![alt text](https://github.com/DalalAL-Alimi/TLIA/blob/main/images/ETR.PNG) 

###  The results of the nine models for the Demand dataset.
![alt text](https://github.com/DalalAL-Alimi/TLIA/blob/main/images/Demand.PNG) 

## Citation
### We would appreciate a citation to the original paper if you use any part of this code (CRV + MHDL or anyone) for your research works.
```
{
  
  AUTHOR = {Dalal AL-Alimi and Ayman Mutahar AlRassas and Mohammed A.A. Al-qaness and Zhihua Cai and Ahmad O. Aseeri and  Mohamed Abd Elaziz and Ahmed A. Ewees},
  TITLE = {TLIA: Time-Series Forecasting Model using Long Short-Term Memory Integrated with Artificial Neural Networks for Volatile Energy Markets},
  JOURNAL = {Applied Energy},
  volume = {343},
  pages = {121230},
  year = {2023},
  issn = {0306-2619},
  doi = {https://doi.org/10.1016/j.apenergy.2023.121230},
  url = {https://www.sciencedirect.com/science/article/pii/S0306261923005949}
  
  }
}
```
