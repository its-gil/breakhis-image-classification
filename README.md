# BreaKHis binary and multi-class image classification for breast cancer recognition

## Purpose and results

The present tool could serve as a starting point in helping doctors detect breast cancer easier.  

The binary model is able to predict with an F1-score of 99% if the cancer is benign or malign, while the multi-class one can differentiate between breast cancer subtypes (Adenosis, Fibroadenoma, Tubular Adenoma, Phyllodes, Ductal Carcinoma, Lobular Carcinoma, Mucinous Carcinoma and Papillary Carcinoma) with an F1-score of 94%.  

The F1-score is a balanced metric used for evaluating models on imbalanced datasets, such as the present one. An F1-score of 100% means that the model can predict every class perfectly correct. 

A detailed scientific report of the project can be read [here](./report/Report_BreaKHis.pdf).

## There are 3 simple steps to replicate this project:

The dataset can be downloaded here: http://www.inf.ufpr.br/vri/databases/BreaKHis_v1.tar.gz ;

1. Download the dataset and put it into **this workspace**. It is critical for step 2.

2. Run the [script for preprocessing the data and creating a file structure](./utils/Preprocess_csv_and_build_file_structure.ipynb) in the folder *./utils* to generate the file index and structure for the images. The creation of the file structure will take a while, because the images have to be scaled down and copied all into the same directory.

3. Run the [binary](./models/Best_binary_model.ipynb) or [multi-class](./models/Best_multiclass_model.ipynb) models under *./models*.

### IMPORTANT NOTE
Ensure that the file paths present in the code are adjusted to your workspace.

## Contributors:
Christian Deluca,  
Gabriele Francesco Zazzetta,  
Michal Wojcik,  
Simon Schumacher,  
Virgil Baclanov @ https://www.itsgil.com  ;
