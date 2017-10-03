# Visualization-Diabetes

This is a visualization of diabetic patient hospital visits in the US. I used the R Shiny libraries to make an interactive web application to explore some of the data. 

The data is from 130 US hospitals between 1999 - 2008. It contains basic patient information (e.g. height, weight, gender, age) as well as information regarding the hospital visit, including: physician specialty, the number of days the patient was admitted, and the number of procedures performed on the patient. 

There is a bubble plot that describes the number of medications prescribed to a patient vs. the number of laboratory procedures performed: 
<p align="center">
<img src="images/bubble_meds.png" width="400"/> 
</p>

A parallel coordinates plot that summarizes the patient/hospital interaction for each medical specialty:
<p align="center">
<img src="images/parallel.png" width="450"/> 
</p>

As well as a collection of bar plots which describe the patient demographics that each medical specialty encountered:
<p align="center">
<img src="images/hist_weight.png" width="450"/> 
</p>

To run the web app, from the R console type:

shiny::runGitHub('Visualization-Diabetes', 'emchinn')
