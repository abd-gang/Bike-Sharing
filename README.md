# Bike Sharing Systems Demand
> The purposen of this assignment is to find and predict the main variables affecting the the demand of rental bikes. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

- We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
- The dataset has been used here is the total no of rental bikes each day from 2018 to 2019 and other variables such as month, year, weekday, temperature, etc. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### After building the model, the 3 main driving factors are-
- As the year increases, the demand of rental bikes is increasing. The year variable has the positive beta coefficient means it is proportional to target variable. 
- If the temperature of the day is more, people tend to rent more bikes. It ahs a very good correlation with the target variable. 
- If the weather is not good - like Snow or Rain, the demand to rental bikes seems decreasing. The beta coefficient of Snow/Rain variable is negative. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.8.8
- Jupyter Notebook - version 6.3.0
- Numpy - version 1.20.1
- Pandas - version 1.2.4
- Matplotlib - version 3.3.4
- Seaborn - version 0.11.1
- statsmodels - version  0.12.2
- scikit-learn - version 0.24.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
#### Created by:
- Akhilesh Gangwar (akhi.gangwar@gmail.com)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->