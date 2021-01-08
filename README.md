# Neihborhoods-Segmentation-and-Clustering

## Problem Description:
**The scenario of this Capstone project**.

Say you live in city **A**. You love your neighborhood, mainly because of all the great amenities and other types of venues that exist in the neighborhood, such as gourmet fast food joints, pharmacies, parks, graduate schools and so on. Now say you receive a job offer from a great company in city **B**. However, given the far distance from your current place you unfortunately must move if you decide to accept the offer.

It would be great if you can find the most convenien neighborhood in city **B**, both in terms of the **lowest distance** from the company headquarters and in terms of the **similarity of the amenities** in your home neighborhood.

## Objective
This porject is aiming to analyze the neighborhoods of both cities (Home and Destination) and group them into similar clusters.
And by analyzing these clusters we can gather meaningful information which will be used to **find out the neighborhoods that are similar to your current neighborhood**.

## Data Description
We are going to use the following data source to achieve our objective:

**List Of All ZIP/POSTAL Codes In JORDAN**: The following page was scraped to pull out all the necessary information:[Dataset source](https://gpsarab.com/shop11/en/content/12-zip-code-in-jordan)

all if the informaiton required for our project are listed in the above link which contains: City name, Neighborhood name, Zip Code for each neighborhood, geographical coordinates (Latitude,Longitude) for each neighborhood.

The information obtained i.e. the table of postal codes was transformed into a pandas data frame for further analysis.

**Foursquare API:** to collect information about the venues in the neighborhoods of Amman and Irbid.

## Methodologies
- Data Scraping.
- Data Wrangling.
- Data Cleaning.
- Data Analysis. 
- Geographic Visualization.
- Unsupervised Machine Learning.
- K-means.

## Technologies
- Jupyter Notebook.
- Python. 
- Pandas.
- Numpy.
- requests.
- BeutifulSoup.
- geopy.geocoders.
- folium.
- sklearn.
- KMeans.

## Results
The goal of this project was to find the most similar and nearest neighborhood to the company headquarter.<br>
Since the home neighborhood in Irbid is **Yarmouk University** and its Cluster is 1
We can see that most of the neighborhoods in Amman are on the same Cluster. <br>
and the most nearest neighborhood in Amman close to the company headquarter with the same amenities is **Jabal Al Hussein Al Gharbi**.<br>
Here is a snapshot of the last map which contains the clusters for each neihborhood for each city.<br><br>

![Neighborhoods Clusters](https://user-images.githubusercontent.com/62763287/104053589-38198a00-51f4-11eb-908f-9d55ace6534a.png)
