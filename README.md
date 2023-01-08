# surfs_up
For SQLite

1. Overview of the statistical analysis:

This analysis to determie temperatures in specific months June and Dec , in order 
to determine , sustainability of business. 
So during this analysis I explored the power of Advanced Data Storage and retrieval to efficiently produce an analysis of temperature trends in Oahu.

Features & Data Sources : 
Data Source : hawaii.sqlite
Programming files : surfup_challenge.ipynb
Data Tools : Python SQL toolkit (SQLAlchemy), Object Relational Maper(ORM), pandas, Numpy
Software : SQLite, Python, Flask , Jupyter Notebook. 

Results : 

There is a bulleted list that addresses the three key differences in weather between June and December.

-
            June Temps     Dec Temps
count       1700.000000    1517.000000
mean        74.944118      71.041529
std         3.257417       3.745920
min         64.000000      56.000000
25%         73.000000      69.000000
50%         75.000000      71.000000
75%         77.000000      74.000000
max         85.000000      83.000000

1. Average recordered temp in June is 74.94 compared to 71.04 in Dec. This represents a -5 degree change in avg temperature from June to Dec. 

2.The June temperatre trends to have a much more normal if compared with all the std meausres like mean, std, min etc.  compared to Dec temp. 

3. Dec temperature shows more deviations in temp if compared with all the std measures. This shows that Dec temps are more flexible flctuating. 
However, Dec is more inline with avg .

Sumarry of Findings : 

In my opinion even though temperatures recorded in december seem to vary more than those of June, December would still provide appropriate weather conditions for both surfing and ice scream. The average temp in june and December only differ by 4 degrees. That makes me feel that temperatures should be one of the measurement to check sustainability of the business but not ultimate measure. There should be other measures involve for understanding and analysing the Sustainability of the business. 


