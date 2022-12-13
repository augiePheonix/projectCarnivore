# projectCarnivore
# Description
We primarily used R studio for our analysis of the data sets provided by the biology department. The raw data we used was provided as a .CSV and .XLSX file. All of the visualizations were created in R studio to analzye data regarding Butterflies and Ladybugs. We wanted to see the wing length, wing width, and apex area by decade, grouped by sex for the butterflies data set. For the ladybugs data set, we wanted to see the count of species characterized by plot, we also saw who collected what species and we also wanted to see common species in IOWA and ILLINOIS. Data dictionary and visualizations are provided below:
#Data Dictionary
#**Data Dictionary

Core ID: Unique identification code assigned to each specie

RW length - measurements of the right wing from the top of right to the bottom

RW width - measurements of the wing from where the wing meets the body to the edge

RW Apex A - peak point of the right wing

LW Length - measurements of the left wing from the top of left to the bottom

LW width - measurements of the left wing from where the wing meets the body to the edge

LW Apex A - peak point of the left wing

**Visualizations

![Rplot](https://user-images.githubusercontent.com/97116253/207204842-41de0c40-943a-42bf-af9a-0c8a641622aa.png)

This combined plot shows the progression of average wing length, average wing width, and apex area over the decades grouped by sex. From these plots we can see that wing length of female butterflies is slighlty higher than that of males over time. For the second plot, wing width is gradually increasing over the years while male wing width is decreasing. The last plot shows us that the average value for apex area is approximately 12 mm^2 for males and 2.5mm^2 for females.
![Rplot01](https://user-images.githubusercontent.com/97116253/207204920-cb649eb3-0fb3-4b6e-80cc-c1428525a033.png)
This plot maps where the cabbage butterflies are collected from. The top map was added to include the butterflies from Europe, while the second one shows which state has the highest number of cabbage butterflies in the US: California. We can also see that females are concentrated on the west coast while males are found on the east coast.
![Rplot02](https://user-images.githubusercontent.com/97116253/207204964-8914a9e0-7362-4ae9-94d3-6eceed5c0575.png)
This plot shows the four different wing measurments grouped by country. We can see that average wing length and average wing width seem to stay consistent accross all the countries. In contrast, apex area is significantly lower in Canada and slightly below average in USA. Anterior spot areas is the highest in The Republic of Ireland.
#**Ladybug 

#**Data Dictonary:

Species: classification comprising related organisms that share common characteristics and are capable of interbreeding

Scan Code: Unique Code given by Augustana to each specie

Collector: The person who gathered the insects

Identifier: The person who identified the kind of species

Country: The country the insects were collected

State: The state where the insects were collected from
#**Visualizations:
![Rplot03](https://user-images.githubusercontent.com/97116253/207205167-1a101cf6-4514-49d0-8a7f-af41f3ae7ea7.png)
This combined plot shows individualt plots of count of species colored by plot code. We can see that plots LP-GU and LP-IC generally have a higher count of species.
![Rplot04](https://user-images.githubusercontent.com/97116253/207205233-2f313a35-8c3a-4d26-84cd-61b8dc9bb460.png)
This combined plot shows individual plots of counts of species colored by Collector.


