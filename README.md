# data_science_assignment
New York City Taxi and Limousine Commission data for Green Taxis This DS challenge is designed to evaluate your skills and intuition regarding a real world data problem. 

Data set: New York City Taxi and Limousine Commission trip records https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page  

The yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.  

We'll use data from Green Taxis for September 2015.  

Load data and analyze:  
1) Characterize the data and comment about its quality 
2) Explore and visualize the data e.g. a histogram of trip distance 
3) Find interesting trip statistics grouped by hour 
4) The taxi drivers want to know what kind of trip yields better tips. Can you build a model for them and explain the model? 
5) Pick one of the options below (Option 1) Find an anomaly in the data and explain your findings. (Option 2) Visualize the data to help understand trip patterns Please submit the result in the form of runnable notebooks or scripts. A link to GitHub or other code repository would be great. Please let us know if we need to do anything special to run your notebook (install packages, get extra data etc.)

## Contents of the repo ##

1. Readme File in .md format
2. Data Dictionary [Pdf](https://github.com/hkhoont/data_science_assignment/blob/master/data_dictionary%20-%20Green%20Taxi%20NYC.pdf)
3. Data preprocessing ipython notebook - Preprocessing till using Dask distributions [Jupyter Notebook](https://github.com/hkhoont/data_science_assignment/blob/master/data_preprocess.ipynb)
4. Data Visulaization and modelling ipython notebook - Orignally done on Google Collab [Collab Link](https://colab.research.google.com/drive/1upuXc2VEjdnERvQFzWLb3gdQDc6NeOiM)

## How to run the files and get the results ##

1. First intall the following library in the Anaconda promp
-geopy
-wget
-xgboost
-geopandas
2. After running the data pre-procesing IPython Notebook - save the resultant DataFrame in the Google Drive
3. Export shared link of this CSV and update the 'link' variable in Google Collab
4. Data Visulaization and modelling ipython notebook - Orignally done on Google Collab. Please open this link on browser on Chrome. Try different browser till you are able to see New York City maps (Bokeh maps) in Google Collab [Please open this link on Chrome/Firefox browser - Collab Link](https://colab.research.google.com/drive/1upuXc2VEjdnERvQFzWLb3gdQDc6NeOiM)
5. If maps were not visible on either of the browsers. The downlaod the [IPython Notebook](https://colab.research.google.com/drive/1upuXc2VEjdnERvQFzWLb3gdQDc6NeOiM). After opening, go to File --> Trust Notebooks --> Complete the by clicking. 
6. If above two methods does not work. The Static Notebook can accessed here [HTML File](https://drive.google.com/open?id=1lUgsTDXq16Gq9dTxg7tWVddQQa3cAd24). Download --> Open in Chrome/Firefox/Safari
