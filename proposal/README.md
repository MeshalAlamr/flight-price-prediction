## Project Proposal (Provisional)

This is the provisional project proposal for the web scraping and linear regression project.

## Question / Need:
#### What is the framing question of your analysis, or the purpose of the model/system you plan to build? 

We plan to predict ticket prices for upcoming flights to help customers in selecting the optimum time for travel and the cheapest flight to the desired destination. 

Throughout this project, a linear regression model will be applied to forecast the cheapest flight tickets to a specific destination based on data scraped from a variety of travel websites such as Momondo, Kayak, and Expedia.

The prediction provisionally will be based on the following features:
- previous flight prices
- destination
- departure
- class
- airline

#### Who benefits from exploring this question or building this model/system?
Flight customers.


## Data Description:
#### What dataset(s) do you plan to use, and how will you obtain the data?
- The dataset will be created by scraping web content from different travel websites.
- The Search Engine Results - Flights & Tickets Keywords Dataset will also be used as it provides Rankings for world top destinations on Google.
#### If modeling, what will you predict as your target?
- Flight prices.

## Tools:
#### How do you intend to meet the tools requirement of the project?
- Using Selenium and BeautifulSoup to perform web scraping.
- Scikit-learn and Statsmodels to perform regression.
- Numpy and Pandas to perform data manipulation.
- Matplotlib , Seaborn , and Tableau for data visualization.
#### Are you planning in advance to need or use additional tools beyond those required?
- We plan to incorporate travel APIs to include real-time data.

## MVP Goal:
The expected outcome of the project is a prediction of flight ticket prices, a dataset that contains scraped data from flight websites and a final presentation.
