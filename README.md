# Data-Engineer-Projects



# Project 1: RFM Customer Segmentation Analysis
* This project goes with:
  1. [Python note book](https://github.com/ThanhNg1712/Data-Engineer-Projects/blob/main/RFM_Customer_Segmentation.ipynb) includes:
      1. Data engineering: Checking, Cleaning missing data, Check classes Balancing
      2. Build classification models: Using clustering to group customer segments, find the optimal number of clusters base on Kmean innertias
      3. RFM analysis: R(Recency), F(Frequency), M(monetary)
         Base on the time customer make a purchase, frequency of making purchases and revunue of an order, we can group customer into three segments: 
         Low Value, Mid Value, High Value base on the total score = R + F + M. The scores are labels that are classified using Kmeans
      5. Visualization 
      
         Frequency vs Revenue
         ![Screen Shot 2022-11-18 at 10 34 14 AM](https://user-images.githubusercontent.com/99359588/202742124-2f054538-e9f8-4024-86a3-0fddf499cf4d.png)
         Recency vs Revenue
         ![Screen Shot 2022-11-18 at 10 36 06 AM](https://user-images.githubusercontent.com/99359588/202742333-75597dd6-6ff2-416f-957e-9c62c474dc42.png)
         Frequency vs Recency
         ![Screen Shot 2022-11-18 at 10 36 46 AM](https://user-images.githubusercontent.com/99359588/202742555-213d7d47-0b05-4bd1-b10e-4a2c202d3522.png)
   
   2. [Dataset](https://github.com/ThanhNg1712/Data-Engineer-Projects/blob/main/OnlineRetail%20(1).csv.zip) can be found here!
         
 # Project 2: Survey Data Analysis
 
 * This project goes with:
  1. [Python note book](https://github.com/ThanhNg1712/Data-Engineer-Projects/blob/main/Excel_project.ipynb) 
      1. This data is a very complicated dataset with 100 columns include
      Question: Questions that are asked participants for their response
      Subquestion: For each question, there are multiple subquestion which are multiple choice for participant to choose
      For a question, if a participant chooses an option, orther options will be N/A
      
      2. This analysis answer this two question
        a) Number of answer for each question
        b) How many respondents answer the same reponse for each question
      3. The analysis using the method: melt dataframe to transpose the data follow question columns, prepare for arregation
     
   2. [Dataset](https://github.com/ThanhNg1712/Data-Engineer-Projects/blob/main/Data%20-%20Survey%20Monkey%20Output.xlsx) can be found here!
