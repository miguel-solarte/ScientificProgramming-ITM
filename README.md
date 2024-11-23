# SCIENTIFIC COMPUTING

# Index

1. [Installing of Necesareis Libraries](#1-installing-of-necesareis-libraries)
   - [Enviroment env](#enviroment-env)
2. [Directory Structure](#2-directory-structure)
3. [Data Constellations mQAM](#3-data-constellations-m-qam)
4. [Preprocessing](#4-preprocessing)
5. [Analysis](#5-analysis)
   

# 1. Installing of Necesareis Libraries 

To work with this repository, you should follow the instructions below.

Note: These instructions are only applicable for Linux systems.

## Enviroment env

```sh
git clone
cd ScientificProgramming-ITM
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
```
# 2. Directory Structure 

```sh
miguel-solarte/ScientificProgramming-ITM
│
├── Data_contellations_m-QAM/
|   |
|   ├── Contellation_16QAM/
|   ├── ideal_contellation_16QAM.csv
│   ├── sintetic_data_16QAM_level90/
|   |   |
|   |   ├── data_16AQM_SNR_5_level90.csv
|   |   ├── data_16AQM_SNR_7_level90.csv
|   |   ├── data_16AQM_SNR_10_level90.csv
|   |   ├── data_16AQM_SNR_12_level90.csv
|   |   ├── data_16AQM_SNR_15_level90.csv
|   |   ├── data_16AQM_SNR_17_level90.csv
|   |   └── data_16AQM_SNR_20_level90.csv
|   |
│   ├── sintetic_data_16QAM_level100/
|   |   |
|   |   ├── data_16AQM_SNR_5_level100.csv
|   |   ├── data_16AQM_SNR_7_level100.csv
|   |   ├── data_16AQM_SNR_10_level100.csv
|   |   ├── data_16AQM_SNR_12_level100.csv
|   |   ├── data_16AQM_SNR_15_level100.csv
|   |   ├── data_16AQM_SNR_17_level100.csv
|   |   └── data_16AQM_SNR_20_level100.csv
|   |
│   ├──  sintetic_data_16QAM_level110/
|   |    |
|   |    ├── data_16AQM_SNR_5_level110.csv
|   |    ├── data_16AQM_SNR_7_level110.csv
|   |    ├── data_16AQM_SNR_10_level110.csv
|   |    ├── data_16AQM_SNR_12_level110.csv
|   |    ├── data_16AQM_SNR_15_level110.csv
|   |    ├── data_16AQM_SNR_17_level110.csv
|   |    └── data_16AQM_SNR_20_level110.csv
|   │
|   ├── Contellation_32QAM/
|   |
|   ├── ideal_contellation_32QAM.csv
│   ├── sintetic_data_32QAM_level90/
|   |   |
|   |   ├── data_32AQM_SNR_5_level90.csv
|   |   ├── data_32AQM_SNR_7_level90.csv
|   |   ├── data_32AQM_SNR_10_level90.csv
|   |   ├── data_32AQM_SNR_12_level90.csv
|   |   ├── data_32AQM_SNR_15_level90.csv
|   |   ├── data_32AQM_SNR_17_level90.csv
|   |   └── data_32AQM_SNR_20_level90.csv
|   |
│   ├── sintetic_data_32QAM_level100/
|   |   |
|   |   ├── data_32AQM_SNR_5_level100.csv
|   |   ├── data_32AQM_SNR_7_level100.csv
|   |   ├── data_32AQM_SNR_10_level100.csv
|   |   ├── data_32AQM_SNR_12_level100.csv
|   |   ├── data_32AQM_SNR_15_level100.csv
|   |   ├── data_32AQM_SNR_17_level100.csv
|   |   └── data_32AQM_SNR_20_level100.csv
|   |
│   └── sintetic_data_32QAM_level110/
|   |   |
|   |   ├── data_32AQM_SNR_5_level110.csv
|   |   ├── data_32AQM_SNR_7_level110.csv
|   |   ├── data_32AQM_SNR_10_level110.csv
|   |   ├── data_32AQM_SNR_12_level110.csv
|   |   ├── data_32AQM_SNR_15_level110.csv 
|   |   ├── data_32AQM_SNR_17_level110.csv
|   |   └── data_32AQM_SNR_20_level110.csv
│   |
|   ├── Contellation_64QAM/
|   |
|   ├── ideal_contellation_64QAM.csv
|   ├── sintetic_data_64QAM_level90/
|   |   |
|   |   ├── data_64AQM_SNR_5_level90.csv
|   |   ├── data_64AQM_SNR_7_level90.csv
|   |   ├── data_64AQM_SNR_10_level90.csv
|   |   ├── data_64AQM_SNR_12_level90.csv
|   |   ├── data_64AQM_SNR_15_level90.csv
|   |   ├── data_64AQM_SNR_17_level90.csv
|   |   └── data_64AQM_SNR_20_level90.csv
|   |
|   ├── sintetic_data_64QAM_level100/
|   |   |
|   |   ├── data_64AQM_SNR_5_level100.csv
|   |   ├── data_64AQM_SNR_7_level100.csv
|   |   ├── data_64AQM_SNR_10_level100.csv
|   |   ├── data_64AQM_SNR_12_level100.csv
|   |   ├── data_64AQM_SNR_15_level100.csv
|   |   ├── data_64AQM_SNR_17_level100.csv
|   |   └── data_64AQM_SNR_20_level100.csv
|   |
|   └── sintetic_data_64QAM_level110/
|       |
|       ├── data_64AQM_SNR_5_level110.csv
|       ├── data_64AQM_SNR_7_level110.csv
|       ├── data_64AQM_SNR_10_level110.csv
|       ├── data_64AQM_SNR_12_level110.csv
|       ├── data_64AQM_SNR_15_level110.csv
|       ├── data_64AQM_SNR_17_level110.csv
|       └── data_64AQM_SNR_20_level110.csv
|
|
├── Preprocessing/
|   |
|   └── Preprocessing.ipynb
|
├── Analysis/
|   |
|   ├── results_QAM/
|   └── Analysis.ipynb
|
├── Figures
|   |
|   └── data_64AQM_SNR_20_level110.csv
|
├── rerults_AQM
|
├── .gitignore
|
└── requirements.md

```

# 3. Data Constellations m-QAM

The dataset of QAM constellations was generated using the MATLAB Communications Toolbox with the purpose of obtaining a dataset containing constellations such as 16-QAM, 32-QAM, and 64-QAM. Non-linear noise was added to each constellation to emulate the conditions caused by light passing through a long optical channel. Additionally, each constellation was varied by adjusting inherent features like signal-to-noise ratio (SNR) with a range from 5 dB to 20 dB, and frequency offset, with values of -90, -100, and -110 dB/Hz at 1 MHz, for a transmission frequency of 10 GHz.Finally, it is important to note that each file with the .csv extension contains 100,000 symbols.


# 4. Preprocessing

In this section, `Preprocessing/preprocessing.ipynb`, you may find various data preprocessing steps, including:

- **Derivation of the image generated for the mQAM constellation**: The derivative was implemented for edge detection. Before applying edge detection, an erosion process is necessary to connect the points. Without erosion, the resulting image will be the same as if only edge detection had been performed.

- **The first part of the spectral clustering algorithm**: Spectral clustering consists of two stages. The first stage involves matrix operations to represent the data in a new space defined by eigenvectors. The second stage applies k-means clustering to the data in this eigenvector space. If k-means is applied directly in the original data space, it cannot properly separate the data. However, when k-means is applied in the eigenvector space, it effectively partitions the data.


# 5. Analysis and Visualization

For the section `Analysis/analysis.ipynb`, various analyses were performed, starting with data visualization using violin plots. This was followed by a statistical analysis of custom data, where ANOVA was conducted. Finally, a data separability analysis was performed by implementing the spectral clustering algorithm and evaluating the results with appropriate performance metrics, such as Bit Error Rate (BER).

In the `Analysis/` directory, there is a folder named `results_QAM`, where you can save the results obtained from performing spectral clustering and evaluating Bit Error Rate (BER).

# 6. Analysis of the computational complexity of Spectral Clustering








