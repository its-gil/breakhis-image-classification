# BreaKHis binary and multi-class image classification for breast cancer recognition

The dataset can be downloaded here: http://www.inf.ufpr.br/vri/databases/BreaKHis_v1.tar.gz ;

## There are 3 simple steps to make this work:

1. Download the dataset and put it into **this workspace**. It is critical for step 2.

2. Run the script *Preprocess_csv_and_build_file_structure* in the folder *./utils* to generate the file index and structure for the images. The creation of the file structure will take a while, because the images have to be scaled down and copied all into the same directory.

3. Run the binary or multi-class models under *./models*.

### IMPORTANT NOTE
Ensure that the file paths present in the code are adjusted to your workspace.

## Contributors:
Christian Deluca,  
Gabriele Francesco Zazzetta,  
Michal Wojcik,  
Simon Schumacher,  
Virgil Baclanov @ https://www.itsgil.com  ;
