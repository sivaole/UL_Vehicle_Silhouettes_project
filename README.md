# UL_Vehicle_Silhouettes_project
# Unsupervised Learning PCA project
Vehicle Silhouettes PCA Analysis

# Problem statement
The purpose of the case study is to classify a given silhouette as one of four different types of vehicle, using a set of features extracted from the silhouette. The vehicle may be viewed from one of many different angles. Four "Corgie" model vehicles were used for the experiment: a double decker bus, Cheverolet van, Saab 9000 and an Opel Manta 400 cars. This particular combination of vehicles was chosen with the expectation that the bus, van and either one of the cars would be readily distinguishable, but it would be more difficult to distinguish between the cars. The purpose is to classify a given silhouette as one of three types of vehicle, using a set of features extracted from the silhouette. The vehicle may be viewed from one of many different angles.

# Abstract
3D objects within a 2D image by application of an ensemble of shape feature extractors to the 2D silhouettes of the objects.

# Data Set Information
The purpose is to classify a given silhouette as one of four types of vehicle, using a set of features extracted from the silhouette. The vehicle may be viewed from one of many different angles.

# Resources Available
The historical data for this project is available in file https://archive.ics.uci.edu/ml/datasets/Statlog+(Vehicle+Silhouettes)

# Attribute Information
ATTRIBUTES

COMPACTNESS (average perim)**2/area

CIRCULARITY (average radius)**2/area

DISTANCE CIRCULARITY area/(av.distance from border)**2

RADIUS RATIO (max.rad-min.rad)/av.radius

PR.AXIS ASPECT RATIO (minor axis)/(major axis)

MAX.LENGTH ASPECT RATIO (length perp. max length)/(max length)

SCATTER RATIO (inertia about minor axis)/(inertia about major axis)

ELONGATEDNESS area/(shrink width)**2

PR.AXIS RECTANGULARITY area/(pr.axis length*pr.axis width)

MAX.LENGTH RECTANGULARITY area/(max.length*length perp. to this)

SCALED VARIANCE (2nd order moment about minor axis)/area ALONG MAJOR AXIS

SCALED VARIANCE (2nd order moment about major axis)/area ALONG MINOR AXIS

SCALED RADIUS OF GYRATION (mavar+mivar)/area

SKEWNESS ABOUT (3rd order moment about major axis)/sigma_min**3 MAJOR AXIS

SKEWNESS ABOUT (3rd order moment about minor axis)/sigma_maj**3 MINOR AXIS

KURTOSIS ABOUT (4th order moment about major axis)/sigma_min**4 MINOR AXIS

KURTOSIS ABOUT (4th order moment about minor axis)/sigma_maj**4 MAJOR AXIS

HOLLOWS RATIO (area of hollows)/(area of bounding polygon)

Where sigma_maj2 is the variance along the major axis and sigma_min2 is the variance along the minor axis, and

area of hollows= area of bounding poly-area of object

The area of the bounding polygon is found as a side result of the computation to find the maximum length. Each individual length computation yields a pair of calipers to the object orientated at every 5 degrees. The object is propagated into an image containing the union of these calipers to obtain an image of the bounding polygon.

NUMBER OF CLASSES

4 OPEL, SAAB, BUS, VAN

# Links:
[Data](https://github.com/sivaole/TermDepositSale_Ensemble_Models/blob/master/bank-full.csv)  
[Link to the report(detailed analysis) - Report]()   
[Source code](https://github.com/sivaole/TermDepositSale_Ensemble_Models/blob/master/TermDepositSale.ipynb)

# Developer:
Sivasankar Vennala
