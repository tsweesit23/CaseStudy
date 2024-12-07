READ ME

TIFFANY WEE SIT CASE STUDY 3

DATA SET: https://www.kaggle.com/code/jacopoferretti/expedia-travels-clustering-the-customer-bookings

SHINY APP: https://clustering-expediadata.shinyapps.io/shiny_app/ 

How to run once you download for RStudio on console: shiny::runGitHub("RepositoryName, "GitUserName", subdir = "shiny_app")


* What data you collected?
I collected travel data specifically booking on Expedia.

* Why this topic is interesting or important to you? (Motivation)
For me this is interesting as the travel industry is very interesting in terms of pricing. Pricing for flights, travel accomodationsd, and how it all comes together.


* How did you analyze the data?
I had to one clean the data as there were missing values in them so I just sweepeed the data so I could ensure when doing an
algorithm it doesn’t cause an error with any duplicated or missing value. I analyzed the data by choosing clustering. This is suitable for this dataset as....

* What is Clustering?
Clustering is a machine learning algorithm in which the algorithm sorts data points in clusters or groupings based on similarity. 
It connects objects from the data set to form clusters based on distance between them. 
Clustering is dependent on your data set and what features you are trying to look into and what questions you want to answer. 
This method can be done simply by packages within python, R, ect. There are certain variables that you can change such as number of clusters or what objects you are looking to cluster.
It is used for knowledge discovery than prediction. Overall gives a better understanding on certain objects within the dataset. 

1.It uses k-means clustering to Place k points into the space represented by the objects
that are being clustered. These points represent initial group centroids.
2. Assign each object to the group that has the closest
centroid.
3. When all objects have been assigned, recalculate the
positions of the k centroids.
4. Repeat Steps 2 and 3 until the centroids no longer move.
This produces a separation of the objects into groups
from which the metric to be minimized can be
calculated.


* What did you find in the data? (please include figures or tables in the report)



The 5-cluster segmentation provides broader, distinct customer groupings. Each cluster reflects a significant behavioral trend, such as frequent domestic travelers, long-distance international vacationers, package deal users, mobile-first users, or family-oriented travelers. This granularity helps businesses target these broad categories with tailored offerings, such as discounted bundles for package users or family-friendly options for large group travelers.



The 10-cluster segmentation uncovers more granular sub-groups, such as niche travelers (e.g., solo adventurers, group package enthusiasts, or short-term bookers). However, overlaps between some clusters suggest that the data might be slightly noisy or certain distinctions are not practically actionable. For example, a cluster with high family travel preferences might be split into families with infants versus families with teens.
