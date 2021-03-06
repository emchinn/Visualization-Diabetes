# Visualization-Diabetes

This is a visualization of diabetic patient hospital visits in the US. I used R Shiny to make an interactive web application to explore some of the data. 

The data is from 130 US hospitals between 1999 - 2008. It contains basic patient information (e.g. height, weight, gender, age) as well as information regarding the hospital visit, including: physician specialty, the number of days the patient was admitted, and the number of procedures performed on the patient. 

There are bubble plots that describe the average number of laboratory procedures performed on diabetes patients compared to other variables in the dataset: 
<p align="center">
<img src="images/bubble_meds.png" width="450"/> 
</p>

A parallel coordinates plot that summarizes the patient/hospital interaction for each medical specialty:
<p align="center">
<img src="images/parallel.png" width="500"/> 
</p>

As well as a collection of bar plots which describe the patient demographics that each medical specialty encountered:
<p align="center">
<img src="images/hist_weight.png" width="500"/> 
</p>

The libraries used include:  
library(tidyr)  
library(ggplot2)  
library(shiny)  
library(scales)  
library(plyr)  
library(reshape)  
library(dplyr)  
library(GGally)  


To run the web app, from the R console type:

shiny::runGitHub('Visualization-Diabetes', 'emchinn')
