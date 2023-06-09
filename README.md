# AntarcticaChangeDetection
Codes used to classify landscape change in Antarctica in Google Earth Engine (JavaScript)

There are two components to this change detection: 1) Initial change detection; and 2) Application of change detection to other sites.

Initial change detection applies to the site that has been identified as representative for training data. In preparation for this analysis, a contempeorary and legacy classification of the site should be available.
Application of change detection to other sites used the training data produced in part 1 to classify change in other regions. 

These methods are based on Xu, R., Lin, H., Lü, Y., Luo, Y., Ren, Y., Comber, A., 2018. A Modified Change Vector Approach for Quantifying Land Cover Change. Remote Sens. 10, 1578. https://doi.org/10.3390/rs10101578.

# 1) Initial change detection

1) Identify what change classes are possible 
2) Generate training data points 
3) Classify the chosen site uisng a random forest classifier
4) Assess accuracy

# 2) Application of change detection to other sites

Use training data set produced in part 1 to classify change at other sites using a random forest classifier
