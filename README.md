# NYC Vehicle Accident Investigation - Person
This was part of the Team 41's group project for Georgia Tech MGT 6203 Summer of 2023 semester.   
This repository only kept the Person dataset analysis, which is my own part of analysis in this project.   
Other parts, including Crash and Vehicle analysis were mainly done by other team members, and aren't included here. 

## Introduction
This project was trying to find the contributing factor for person's injury/death in vehicle accidents, then build a logistic regression model to make prediction. Confusion Matrix and ROC Curve were used to evaluate the model.  
Please check details in **"Person dataset results.pdf"**. 

Evidence from Person dataset indicates:   
1) Use of safety equipment significantly contributes to the difference between life and death.   
   Companies can leverage the importance of safety equipment in their advertising by emphasizing how their products or services prioritize customer safety.  
2) Higher involvement of male drivers in accidents.  
   Government and transportation authorities could utilize result to encourage male drivers to adopt more cautious driving behaviors.  
3) Age group [25-35) ranks the highest percentage in both injured and killed in vehicle accidents.

## Data Download Instruction    
If **raw data** downloading is needed for R code, please download from the following websites.     
Motor_vehicle_Collisions - Person: https://catalog.data.gov/dataset/motor-vehicle-collisions-person    841 Mb    
Original csv files were downloaded 6/15/2023 through above websites, and data sizes as shown.    
However, DATA.GOV updates the above data regualarly, so if use newly downloaded csv files, R code results might be a little different from group's final report.     

## Presentation video
Proposal: https://www.youtube.com/watch?v=bp6K5hLZpYc    
Final: https://www.youtube.com/watch?v=L_AgN_qxl_s

## R code Running Instruction
Please be patient, due to sizes of csv files, it will take a few minutes to load data, clean data and running other R code commands.    
Use **raw data** to clean rows then use 50% threshold to clean columns. Please be patient, it will take a few minutes to load data and clean data. 
For detailed running instructions, please follow markdowns in **"NYC Vehicle Accident Investigation - Person.Rmd"** file. For a results report including visualizations without running code, check out **"NYC-Vehicle-Accident-Investigation---Person.pdf"**.  
  
## Visualization
Check out **"NYC-Vehicle-Accident-Investigation---Person.pdf"** for Person visualization.
