# Real_estate project
 Analysis of King County real estate data

Author: Tisa Yip

## Overview

Regression analysis of King County Real Estate data to predict house prices.


## Business Problem

This information could be used by real estate agencies to evaluate what a property could be currently sold at within King County.

## Data Understanding

The data used in this analysis is from King County. <br>This dataset contains relevant information recent homes sold and their details so there are a good set of variables to base the models on.

## Data Modeling

<li>1st iteration of the raw data. The Q-Q plot shows that the data is skewed as it's curves away from the line 
</li>
<img src="https://github.com/xSTILETTOx/Project2_Xi/blob/main/image.png" alt="Alt text" style="max-width: 100%;">
<br>
<li>Heatmap and histogram of raw data</li>
<img src=https://github.com/xSTILETTOx/Project2_Xi/blob/main/heatmap_raw.png alt="Alt text" style="max-width: 100%;">
<br>
<li>Next, the data was scaled to a normal distribution. Normality met. Assumptions hold.</li>
<img src=https://github.com/xSTILETTOx/Project2_Xi/blob/main/image-3.png alt="Alt text" style="max-width: 100%;">
<br>
<li>Heatmap and histogram of scaled data.</li>
<img src=https://github.com/xSTILETTOx/Project2_Xi/blob/main/heatmap_scaled.png alt="Alt text" style="max-width: 100%;">
<br>
<li>Lastly, dummy variables were added and log transformation done. Normality met. Assumptions hold. Has a tighter fit compared to the scaled model</li>
<img src="https://github.com/xSTILETTOx/Project2_Xi/blob/main/image-2.png" alt="Alt text" style="max-width: 100%;">
<br>
<li>Table of MSE and MAE</li>
<img src="image-5.png" alt="Alt text" style="max-width: 100%;">

## Evaluation
From the raw data sqft_living and grade correlate highly with price. Sqft_living slightly more than grade.

Once the data is scaled it shows grade has more influence on the price than sqft_living.

MSE for scaled data is 0.8 difference train/test and the MSE for log data is 0.96 which shows that the scaled data produced a slightly more accurate predictor model than the log transformation.


## Conclusions
 We thoroughly inspected the model parameters, vetted that assumptions hold good.</li>
<li> The accuracy of the models did not increase much after scaling. </li>
<li> They may not be the best when it comes to accurate predictions, however they help us answer basic questions better, such as "which characteristics influence the cost of a home, is it how much square footage or the grade which King County assign to a property"?. In this case it's the grade by a fraction.</li>

## For More Information
See the full analysis in the <a href=https://github.com/xSTILETTOx/Project2_Xi/blob/main/Project2_Final1.ipynb>Jupyter Notebook</a> or review this <a href="King_County_Presentation.pdf">presentation.</a>

For additional info, contact Tisa Yip at 
<a href="mailto:clawspawsandjaws@gmail.com"> clawspawsandjaws@gmail.com </a>
