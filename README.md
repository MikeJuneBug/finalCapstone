# finalCapstone
Final Capstone Project: Principal Component & Cluster Analysis on the 50 State 1973 US Arrest Dataset

This project aims to briefly explore the 50 State 1973 US Arrest Dataset, produce PCA and cluster analysis, find and interpret commonalities in the clusters. 

Table of Contents

    Installation
    How to Use (inc screen shots)
    Credits and Links
    

Installation

This main project file is in a Jupyter notebooks. The data file is a CSV. 

Requirements: Python 3.x 
Libraries needed to be installed:

    Pandas version 1.5.2 
    Numpy version 1.24.0
    Matplotlib version 3.6.2
    Scipy 1.9.2
    Sklearn 1.2.0
    Seaborn 0.12.2

Once the necessary libraries have been installed, clone the repository from GitHub using the following command:
!git clone https://github.com/MikeJuneBug/finalCapstone

This will create a new directory on your local machine with the files from the repository. Go to this directory in your Jupyter Notebook and open it


How To Use

Run each cell from the top in the jupter notebook. The file runs through uploading, inspecting the data, preprocessing, 
checking for correlations, running a PCA on non-standardised data, standardising and running a PCA on the standardised data, 
producing dendrograms and K-means.

Histogram of Murder Data
![image](https://user-images.githubusercontent.com/106621067/211005557-2c594b32-0329-4e16-96b3-fd5da833f9a5.png)

Seaborn Heatmap Correlation Plot:
![image](https://user-images.githubusercontent.com/106621067/211006199-ca5b5d1f-9cef-45c4-b221-4c9d4520e0ac.png)

Biplot of Principle Component 1 and Principle Component 2 - Standardised Data Version
![image](https://user-images.githubusercontent.com/106621067/211006286-140277c1-27bd-4464-bfc4-0e2f8426dd11.png)

The main findings can be found in the jupyter notebook file.


Credits and Links

Author: Michael Sullivan 
Contact via https://www.linkedin.com/in/michael-s-940b43252/

Thanks to 
HyperionDev https://www.hyperiondev.com/
Python Data Science Handbook https://jakevdp.github.io/PythonDataScienceHandbook/



