# Toronto-Neighborhoods-Analysis using ML
This analysis is inspired from a conversation among me and other Vietnamese students who has studied, lived in Finland and thinking about a good place outside Finland to experience later on.  <br />
Jupyter Notebook, Report, Blog are included with links.  <br />


## Introduction
Imagines that we, Vietnamese students have lived in Finland for a long time, would like to know the good places to live in Canada. One of teh most important questions could be asked is “What neighbourhood in Canadia should I live in?”. Therefore, this project aims to group Toronto neighborhoods using ML, Data Analytics and Data Visualization techniques to answer that questions better. <br />

Some _**criteria**_ I use to analyse:  <br />
* Total number of **Essential Venues** of every neighbourhood  <br />
* **Primary and Secondary Benchmarks**: Primary benchmarks are Unemployment Rate, Crime Rate and COVID-19 rates. Secondary benchmark are  Housing Price for a one-bedroom apartment   <br />

## Method
### Python Libraries
I use: 
* Pandas:  For storing and manipulating structured data. Pandas functionality is built on NumPy
* Numpy:   For multi-dimensional array, matrix data structures and, performing mathematical operations
* Geopandas:  For storing spatial data coordinates and shape files
*	Scikit-learn:For Machine learning tasks
* Plotly      : For all visualizations (including maps and graphs)
*	Requests    :  to send HTTP requests easily
*	Geopy       : To retrieve location coordinates <br />

### Machine Learning: _**K-Means**_
K means is an Unsupervised Machine Learning algorithm that groups data into k number of clusters that groupss the neighbourhoods into “k” (with similar characteristics or qualities). Steps that algorithm works:
* (i) Determines most optimal k (i.e. no of clusters)
* (ii)Initializes k such that initial means are randomly generated within the data domain
* (iii)Creates k clusters by associating every observation with the nearest mean
* (iv)The centroid of each of the k clusters becomes the new mean
 Steps (iii and iv) are repeated until convergence is reached such that all data points belong to a cluster that are significantly distinct from one another <br />

K-means and _**Choropleth Map**_ are used to get final index of Neighbourhood Desirability

### Conclusion
 The project runs well enough with visualisations.
 Neighbourhood Desirability are  performed as:
- The small amount of high venue density neighborhoods. This helps to limit of favorite options of desirable neighborhood
- Most Desirable Neighbourhoods:
- Entertainment Districts: These data are good for who loves entertainment
- Essentail Venues:
- Unproper Neibourhoods that users should avoid based on the high Crime Rate, Covid Rates

These results could be used to make decisons for individuals who eants to find a good place to setle down. 


## Plan for improvements

In the future, I hope this project is impoved enough for government who want to make better policies for distributes people properly to specific areas.
Factors should be improved:
- Codes: be optimized more: shorter and still effective
- Visualise: make betetr stable when running this function. Try to visualise them in Power Bi, Tableau.

