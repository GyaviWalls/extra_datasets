# Income prediction

### Author: Ayebare Gyavira

"Never make a trade or take an action unless it's backed by reason and analysis." - William J. O'Neil

Companies have a tendency to ask for how much an applicant is comfortable with as salary. This can be decided based on a number of factors plus other considerations. In predicting this, it allows applicants to estimate how much a company's worth and if they can afford to work their given the company's expectations and environment. In this project, we look at some of the features and how they affect whether someone earns less that a 50k within a certain company.

### Data Source:

Adult income dataset [https://www.kaggle.com/datasets/wenruliu/adult-income-dataset](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset)

In the original dataset, there werer 48,842 rows and 15 columns.

### Data Dictionary

| Feature Name | Description |
|:--------:|:--------:|
|  Age |  The individual's age  |
|  Workclass |  The working class of the individual  |
|  Fnlwgt	  |  The final weight of the individual  |
|  Education	  |  The level of education the individual attained  |
|  Education-num |  The education number of the individual  |
|  Marital status  |  The current maritual status that the individual's in  |
|  Occupation   |  Name of where the individual works   |
|  Relationship	  |  What responsibility the individual holds in the family |
|  Sex |  The individual's gender  |
|  Race |  The individual's race if they are at liberty to give it out   |
|  capital-gain |  The gains in capital the individual makes while working  |
|  capital-loss |  The loss in capital the individual makes while working  |
|  Hours-per-week |  The number of hours the individual places into working  |
|  Native-country |  The country of origin of the individual  |
|  Income |  Whether the individual earns above 50k or below. This is the target variable to be predicted  |


To prepare this data, the data was cleaned, and the following processes were performed:

### Exploratory Data Analysis

- To visualize the data for explantory purposes, bargraphs were used.
- The bargraph was chosen to show how the working class categories varry with hours per week worked based on whether an income of above 50k or not is earned.
- The bargraph shows that in all the working classes, those who work for more hours per week earn above 50k compared to those who don't with the exception of those who've never worked it seems that they all receive below 50k. That might be the default amount or something.

![workclass_hours](https://github.com/GyaviWalls/extra_datasets/assets/44253554/6633da22-a07e-4249-894a-02796ec6e6ca)

This bargraph shows that the older someone is irrespective of their education level, they earn above 50k. Its most likely an advantage of being more experienced or holding more responsibilities.

![education_age](https://github.com/GyaviWalls/extra_datasets/assets/44253554/543d16b8-e06c-4227-b13b-b0a63aea4ff9)

