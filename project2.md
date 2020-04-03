# Project 2: Jamaica

Henry Buron

## Part 1

Histogram representing population distribution of Jamaica's 14 Parishes.

![](jam_histogram99.png)

Density plot.

![](jam_density99.png)

Histogram of population distribution combined with probability density function.

![](jam_pdf_log99.png)

Residual model with regression line and confidence interval representing the correlation of night time lights, urban cover, and bare cover with Jamaica's population distribution.

![](jam_some_variables99.png)

Residual model with regression line and confidence interval representing the correlation of all variables with Jamaica's population distribution.

![](jam_all_variables99.png)

## Part 2

### Jamaica - adm1

![](jamaica_diff1.png)
The above plot shows the difference (error) of predicted value from the worldpop raster in Jamaica. The error appears to be relatively consistent - slightly above 0 (overestimation) - throughout most of Jamiaca, though in the Saint Catherine/Saint Andrew/ Kingston area, the error dips down to -30. This represents a large underestimation, which makes sense because this is the most highly and densly populated area of Jamaica.

![](jamaicapop_proj2_part2.png)
This plot shows the actual population values of Jamaica from the worldpop site. If you compare this plot to the previous one, you will see that the areas of high population are more likely to be underestimated, and the areas of low population are more likely to be overestimated.

![](jamaica_3d)

This is a 3D plot of Jamaica that reprsents how much variation was exhibited in the predicted values.

![](jamaica_mapview.png)
This plot is a mapview that also reprsents the error of the predicted values compared to the worldpop raster. As you can see, population values were underestimated near Kingston, the capital, and generally overestimated throughout the rest of the country.

### Saint Catherine - adm2

![](saint_catherine2.png)
The above plot shows the difference (error) of predicted values from the worldpop raster in the Jamaican provice Saint Catherine. The areas of overestimation appear in spots towards the south east and south west, which makes sense as that is where the largest cities are located.

![](saint_catherine1.png)
This plot shows the actual population values of Saint Catherine from the worldpop site. If you compare this plot to the previous one, you will see that the areas of high population are more likely to be underestimated, and the areas of low population are more likely to be overestimated.

![](saint_catherine3d)

This 3D plot is meant to represent the variation exhibited in the predicted values. However, as you can see, the plot currently does not really represent anything. I am working on fixing this issue.

![](saint_catherine_mapview.png)
This plot is a mapview that also reprsents the error of the predicted values compared to the worldpop raster. The model overpredicted in areas of high population and under predicted in areas of low population. It's interesting to note that the underprediction error seems to generally be larger than the overprediction error.
