# Jupyter Notebooks

This repository contains 2 Jupyter notebooks and some related files for the purpose of introducing 3 plots from the `matplotlib.pyplot` package, and demostrating a data analysis of CAO data from 2019 to 2021. 

<br>

### **pyplot folder**
The **pyplot notebook** contains an overview of the `matplotlib.pyplot` packgage and some simple demostration using the Iris dataset (`iris.csv`). It then goes on to introduce 3 plots from the package, namely *Horizontal barchart*, *Pie chart* and *Heatmap*, with demostrations.

<br>

### **CAO folder**
The second notebook in the repository is **CAO notebook**. There are several folders inside it, `CAO original data` contains original data of 2019-2021 extracted from CAO website, `CAO2019`, `CAO2020`, and `CAO2021` folders contains data in csv format with time stamps. 

The notebook demostrates 3 ways to extract data from an online source as CAO data of 2019, 2020, and 2021 are in pdf format, excel format and as html respectively. After loading data of 2019-2021 into data frame, they are concatenated into 1 pandas dataframe. The last part is an analysis comparing CAO data between 2019, 2020 and 2021 illustrated with some plots. 

## Requirements

- Anaconda <br>
    1. If you have already downloaded and launched Anaconda, Jupyter should be installed already. Move on to the next section
    2. If Jupyter has not been installed, first make sure pip is up-to-date. Open cmder and type in <br>
    `python -m pip install --upgrade pip` <br>
    then type the command to install Jupyter <br>
    `python -m pip install jupyter` <br>
<br>
- Camelot <br>
    1. Install Camelot using Anaconda. Open cmder and  type in <br>
    `conda install -c conda-forge camelot-py` <br>
    then follow installation instruction on screen. 

## Run

After pulling the repository to your own machine, 

1. Open terminal or cmder
2. Move to the directory where the repository is stored
3. Type in `jupyter lab` or `jupyter notebook`, it will open a new browser
4. Go to browser, run the notebook from top to bottom. 

<br>

## Explore
### pyplot notebook
Three kinds of plots were introduced in the notebook, tweak the data supplied to plots or change the parameters of plots to see how the plots changed. 