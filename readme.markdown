# MLB Pitchers Clustering and Expected Run Value Prediction Model
The datasets used in this project were too large to be uploaded to GitHub. Please download the entire `data` file from [here](https://drive.google.com/drive/folders/1k0Zs1J9dhEeZBnzbh3Mtv4GgUWBMGtit?usp=sharing), and place it outside the working directory of the notebooks, like this:

1. data
   1. dataset1
   2. dataset2
2. main
   1. notebook1
   2. notebook2

\
`cluster_analysis`: exploratory data analysis on each cluster of Pitchers.

`cluster_modeling`: run clustering algorithms on pitchers data and measure prediction. results. ***CAUTION: this notebook takes several hours to run entirely.***

`functions`: some functions used in the modeling process.

`get_statcast`: retrieve Statcast data.

`pitcher_data_cleaning`: clean data which are used in cluster modeling process.

`RV_calculation`: calculate RE24 and run values on PA data.

\
Also, some libraries need to be installed to fully run the scripts:
1. Scikit Learn
2. Scipy
3. Numpy
4. Pandas
6. tqdm
7. Matplotlib
8. Seaborn
