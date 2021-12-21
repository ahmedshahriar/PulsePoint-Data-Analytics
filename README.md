# PulsePoint Data Analytics
[![Made with Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?logo=Jupyter)](https://jupyter.org/try)  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ahmedshahriar/PulsePoint-Data-Analytics/main) [![Open in Visual Studio Code](https://open.vscode.dev/badges/open-in-vscode.svg)](https://github.dev/ahmedshahriar/PulsePoint-Data-Analytics) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/ahmedshahriarsakib/pulsepoint-emergency-analytics) [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](http://nbviewer.org/github/ahmedshahriar/PulsePoint-Data-Analytics/blob/main/PulsePoint_Emergency_Analytics.ipynb)

![](https://calchamberalert.com/wp-content/uploads/emergency.png "credit : https://calchamberalert.com/2017/10/20/what-employers-should-know-about-emergencies-and-the-workplace")

## Summary

In this project I performed data cleaning & preprocessing, feature extraction, extensive geospatial and time series analysis of the Pulsepoint Emergency Data as well as apply some clustering and dimensionality reduction techniques.

## Dataset
 
PulsePoint offers a web client at [web.pulsepoint.org](https://web.pulsepoint.org) that allows users to view the same data that appears in PulsePoint Respond with a browser.

The dataset was collected via web scraping using python libraries. The logs were collected from **2021-05-02** to the Present.

### Source
- [PulsePoint Respond Local Threats And Emergencies](https://www.kaggle.com/ahmedshahriarsakib/pulsepoint-respond-local-threats-and-emergency)

With this data, it is possible to assess the impact of local emergencies over the period as well as the regions where they were concentrated.

The project answers questions which could be inferred from this dataset, such   as:

Location-based: 
- What are the major incidents in terms of numbers?
- What are the major states in terms of the number of incidents? 
- What are the major cities in terms of the number of incidents?
- Which regions have the highest number of incidents?

Time-based: 
- Which dates have a higher number of incidents occurred?
- Which days of the week have a higher number of incidents occurred?
- Which time of the day has a higher number of incidents occurred?

Analysis:
- Find geolocations of the major locations
- Visualize major locations taking the number of incidents that occurred at those regions into account
- Cluster cities based on the time, duration, and the number of incidents that occurred at those places

#### This project also serves as my assignments for the course -
- [IBM Unsupervised Machine Learning](https://www.coursera.org/learn/ibm-unsupervised-machine-learning?specialization=ibm-machine-learning)
#### Also, you can view this notebook on kaggle - 
- [ahmedshahriarsakib/pulsepoint-emergency-analytics](https://www.kaggle.com/ahmedshahriarsakib/pulsepoint-emergency-analytics)
 
#### Preview -

![](https://github.com/ahmedshahriar/PulsePoint-Data-Analytics/blob/main/files/pulsepoint_incidents_by_states_800px.gif)
<br/><br/>
![](https://github.com/ahmedshahriar/PulsePoint-Data-Analytics/blob/main/files/pulse_point_us_states.png)
![](https://github.com/ahmedshahriar/PulsePoint-Data-Analytics/blob/main/files/pulse_point_ca.png)
![](https://github.com/ahmedshahriar/PulsePoint-Data-Analytics/blob/main/files/pulse_point_us_states_heatmap.png)

<br>

### Built With

```
tqdm==4.62.3
wordcloud==1.5.0
geopy==1.17.0
plotly==4.4.1
folium==0.8.3
geopandas==0.10.2
pdpipe==0.0.70
yellowbrick==1.3.post1
scikit-learn==0.22.2.post1
```




