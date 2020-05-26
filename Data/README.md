# Generating dataset

## Datasets:
The required data has been procured from the following sources: \
1) https://www.kaggle.com/c/rsna-pneumonia-detection-challenge
2) https://github.com/ieee8023/covid-chestxray-dataset
3) https://github.com/agchung/Figure1-COVID-chestxray-dataset
4) https://github.com/agchung/Actualmed-COVID-chestxray-dataset
5) https://www.kaggle.com/tawsifurrahman/covid19-radiography-database

## Generating Dataset:
Create an src and input directory and run the following commands in the input directory:
* `git clone https://github.com/ieee8023/covid-chestxray-dataset.git`
* `git clone https://github.com/agchung/Figure1-COVID-chestxray-dataset.git`
* `git clone https://github.com/agchung/Actualmed-COVID-chestxray-dataset.git` 

Download the remaining datasets using the links:
* [COVID-19 Radiography database](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database) to download the COVID-19 Radiography database. Only the COVID-19 image folder and metadata file is required. 
* [RSNA Pneumonia Dataset](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/data)

### Run the following codes in order(src folder):
* Run this [code](../Codes/rsna_preprocess-Github.ipynb) for allocating the rsna dataset.
* Run this [code](../Codes/covid_preprocess-Github.ipynb) for integrating the COVID datset with rsna.

