# Dry-Beans-Classification
Predict the type of a dry bean from its shape features

# Get Score on Kaggle 93%

# Data Set Information:

Seven different types of dry beans were used in this research, taking into account the features such as form, shape, type, and structure by the market situation. A computer vision system was developed to distinguish seven different registered varieties of dry beans with similar features in order to obtain uniform seed classification. For the classification model, images of 13,611 grains of 7 different registered dry beans were taken with a high-resolution camera. Bean images obtained by computer vision system were subjected to segmentation and feature extraction stages, and a total of 16 features; 12 dimensions and 4 shape forms, were obtained from the grains.

# Data fields

ID - an ID for this instance
Area - (A), The area of a bean zone and the number of pixels within its boundaries.
Perimeter - (P), Bean circumference is defined as the length of its border.
MajorAxisLength - (L), The distance between the ends of the longest line that can be drawn from a bean.
MinorAxisLength - (l), The longest line that can be drawn from the bean while standing perpendicular to the main axis.
AspectRatio - (K), Defines the relationship between L and l.
Eccentricity - (Ec), Eccentricity of the ellipse having the same moments as the region.
ConvexArea - (C), Number of pixels in the smallest convex polygon that can contain the area of a bean seed.
EquivDiameter - (Ed), The diameter of a circle having the same area as a bean seed area.
Extent - (Ex), The ratio of the pixels in the bounding box to the bean area.
Solidity - (S), Also known as convexity. The ratio of the pixels in the convex shell to those found in beans.
Roundness - (R), Calculated with the following formula: (4piA)/(P^2)
Compactness - (CO), Measures the roundness of an object: Ed/L
ShapeFactor1 - (SF1)
ShapeFactor2 - (SF2)
ShapeFactor3 - (SF3)
ShapeFactor4 - (SF4)
y - the class of the bean. It can be any of BARBUNYA, SIRA, HOROZ, DERMASON, CALI, BOMBAY, and SEKER.
![__results___15_0](https://user-images.githubusercontent.com/94288063/141685661-61a5a50c-dd28-4b40-9f04-ffe9fab83fb3.png)

