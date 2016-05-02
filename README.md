###Data Mining Project
#####Using other Awards to predict Oscar winners
============================================================

## OVERVIEW
Oscar it been the most awaited prestigious awarding ceremony for movie lovers across the globe and we would like to consider the other award ceremony that were given out in the run-up to the Oscars. We use this data and predict the Best Director, Best Film, Best Actor, Best Actress and Best Actor in Supporting role and Best Actress in supporting role. 
We would give weights to each of these awards in the selected categories. These weights would be based on previous year’s data. Like for example Agro won Oscar for best film in previous year. We would give more weightage to the awards above who have selected Argo as best picture in that year. Similarly we would do this kind of analysis on previous years and finally predict Oscars using those weights for this year.

## DATA
We are planning to follow these awards from the following websites data 

1. Directors Guild of America (http://www.dga.org/)
2. Producers Guild of America (http://www.producersguild.org/)
3. Screen Actors Guild (http://www.sagawards.org/)
4. Bafta (http://awards.bafta.org/)
5. Writers guild of America (http://www.wga.org/)
6. Golden Globe (http://www.goldenglobes.com/)
7. American Cinema Editors (https://americancinemaeditors.org/)
8. Critics Choice movie Awards (http://www.criticschoice.com/movie-awards/)
9. Chicago film Critics Association (http://www.chicagofilmcritics.org/)
10. National Board of Review (http://www.nationalboardofreview.org/)
11. NY film Critics circle (http://www.nyfcc.com/)


## RESEARCH QUESTIONS
We would like to predict the Oscar for this year by using the above data from different awarding sites by Retrieving Winners of above mentioned awards from their websites for the past 5 years.
 Perform clustering algorithms on them to see their distances from Oscars. The reciprocal of distances would be our weights
 Using the above weights over the years predict Oscars of this year. From this year’s awards data.

## MODELS AND ANALYSIS
We are planning our models and preliminary analyses will be performed in a Jupyter Notebook and development in python.


## CODE AND APPLICATION
We are considering to collaborate on developing the Web API and implementation of code and post the code in our GitHub repository and instructions on installation are in the README.md file at the root level.


## PROJECT MANAGEMENT
Our team consists of five members, Varun Reddy Sallagonda, Sai Abhijith Kowluru, Mahesh Thoutam, Dayakar Pattipati, Srinitha Koralla. we will be sharing our work among ourselves. Varun Reddy will be taking care of development and data analysis. Sai Abhijith and Mahesh will be working on Back end work consisted of an API that was created to provide data to the front end. And Writing O Auth script to pull linked in Connections. Dayakar and Srinitha would work on data set, data analysis and UI development and together we are collaborating to check the progress of the project testing. 

### PROJECT TEAM, DELIVERABLES AND CHECKPOINTS

## TEAM

| Team member | Roles and skills | Contributions |
|-------------|-------------------------|---------------------------------------------|
| Varun Reddy Sallagonda | Data analysis, Testing | data analysis, Testing, build scripts |
| Sai Abhijith Kowluru  | data analysis, Python | development, data analysis, Python | 
| Mahesh Thoutam | data analysis, Python | development, data analysis, Python |
| Dayakar Pattipati| Testing, Data analysis | Data analysis, test harness |
| Srinitha Koralla| Testing, Data analysis  | Data analysis, test harness |

## DELIVERABLES AND CHECKPOINTS


| Checkpoint date | Expected Deliverable                                                          | Responsibles Team Members(s) | Checkpoint results                                                                                                                  |
|-----------------|-------------------------------------------------------------------------------|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
|02/15/2016 |Using other Awards to predict Oscar winners (analysing and collecting the data about our project details)  | All team members  | Check point 1 completed| 
| 03-08-2016| Creating  a template on how data is collected, like how many points for winners, nominees and cases of tie, Creating a common template for all awards on how it needs to be stored, for example what is the index and what are the columns etc, Collected data from Wikipedia of winners and nominees.This is a big task as the data is not at one place and we are going back to 2005 data.| Varun Reddy, Sai Abhijith & Mahesh Thoutam| Analysed data from the other awards till now & developed the algorithm|
| 04-11-2016 | we have completed data segregation of best film form other awards and have project the final result of best film prediction for Oscar's from our data .And, further we have completed data collection for different categories of Oscar's and planning to complete the prediction of these categories in future checkpoints.| Varun Reddy, Sai Abhijith | Mini Check point completer |
| 04-18-2015 | We have completed the data collection from past 2 weeks and done predicting the oscar prediction from other awards for best film , best actor , best actress by implementing  linear regression in Python using scikit-learn model  and by 25th we are planing to complete the same for best actress in supporting and best actor in supporting | All team members | CCheckpoint 3 completed|
| 04-25-2016 | we have completed Oscar prediction for best director ,best actress in supporting and best actor in supporting roles |
Srinitha Koralla,Mahesh Thoutam | Check point 4 completed| 



