## Project 4

### Title: Web Scraping Job Postings 

### Business Case:

#### You're working as a data scientist for a contracting firm that's rapidly expanding. Now that they have their most valuable employee (you!), they need to leverage data to win more contracts. Your firm offers technology and scientific solutions and wants to be competitive in the hiring market. Your principal has two main objectives:

#### Determine the industry factors that are most important in predicting the salary amounts for these data.
#### Determine the factors that distinguish job categories and titles from each other. For example, can required skills accurately predict job title?
#### To limit the scope, your principal has suggested that you focus on data-related job postings, e.g. data scientist, data analyst, research scientist, business intelligence, and any others you might think of. You may also want to decrease the scope by limiting your search to a single region.

### Hint: 
#### Aggregators like www.mycareersfuture.sg regularly pool job postings from a variety of markets and industries.

### Goal: 
#### Scrape your own data from a job aggregation tool like Indeed.com in order to collect the data to best answer these two questions.

### Directions
#### In this project you will be leveraging a variety of skills. The first will be to use the web-scraping and/or API techniques you've learned to collect data on data jobs from Indeed.com or another aggregator. Once you have collected and cleaned the data, you will use it to answer the two questions described above.

### QUESTION 1: Factors that impact salary

#### To predict salary you will be building either a classification or regression model, using features like the location, title, and summary of the job. If framing this as a regression problem, you will be estimating the listed salary amounts. You may instead choose to frame this as a classification problem, in which case you will create labels from these salaries (high vs. low salary, for example) according to thresholds (such as median salary).

#### You have learned a variety of new skills and models that may be useful for this problem:

#### NLP
#### Unsupervised learning and dimensionality reduction techniques (PCA, clustering)
#### Ensemble methods and decision tree models
#### SVM models

#### Whatever you decide to use, the most important thing is to justify your choices and interpret your results. Communication of your process is key. Note that most listings DO NOT come with salary information. You'll need to able to extrapolate or predict the expected salaries for these listings.
