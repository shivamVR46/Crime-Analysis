# Crime-Analysis
In this project, we locate four coordinates ([longitude, latitude]) (-73.59, 45.49), (-73.55,45.49), (-73.55, 45.53), (-73.59, 45.53) in the center of Montreal downtown area. 
The bluesquare in the screenshot (see Figure 1.1) shows the located area. All the crime data in this
area are saved in the file “crime_dt.shp”, which includes all the crime data considered at
different points. The dataset is fetched and modified from the City of Montreal's open
data portal.

Using this located area, you need to generate grids in this area to compute the crime rate
statistics in each grid. The size of each grid could be changed due to the distribution of
crime; however, your program should be flexible to change the size of each grid when it
is required.

Crime rates are considered as the number of points in each block defined by the grid. The
crime rates need to be calculated using statistics such as total count, mean, standard
deviation in your results. A threshold of crime rate is introduced to define the high crime
rate blocks and low crime rate blocks in the area selected. The threshold would be
arbitrarily chosen. For example, if you choose the threshold using the median (the crime
rate of a block higher than 50% of the crime rates of total blocks), blocks with the crime
rate higher than median are labelled in yellow (highly risky blocks), and blocks with the
crime rate lower than median are labelled in dark blue (less risky blocks). According to each threshold, the crime rates in the located area will be presented as the following
graphs.
