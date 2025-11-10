# Retail Sales Analytics 

**Project Content ** 
- README.md
- Project Board 
- Dataset
- Jupyter Notebook 
- Dashboard 

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Project Overview 
- In this project , I analysed retail sales data to discover trends, patterns and performance drivers across stores and products. 
- The goal was to practise a full data-analysis workflow -from cleaning and exploration to building a simple machine-learning model and visual dashboard. 
- I wanted to understand what effects sales the most, whether certain stores or product categories perform better, and how this information can support business decisions. 




## Dataset Content
* The dataset was sourced from Kaggle (sales Forecasting Dataset by Rohit Sahoo).

It contains :
- Daily sales transaction by store and project 
- Date , Item number, and units sold 
- Historicatl sales across multiple stores 

Before analysis, i cleaned the dataset by handling missing values, renaming columns and converting data types for easier manipulation. 
The cleaned version is saved as Cleaned_sales_data.csv. 
  


## Business Requirements
The analysis focuses on understanding overall sales trends over time. 

Key goals include: 

- Identify overall sales trends over time. 
- Compare product and store performance. 
- Detect seasonal or monthly patterns. 
- Build a basic Linear Regression model to forecast future sales. 
- Present key findings in a clear interactive dashboard. 

These Questions Guided my analysis and visualisation design. 

1. Which factors drive sales performance?
2. Are there seasonal or regional patterns? 
3. Can a basic regression model predict next month's sales? 


## Hypothesis and how to validate?

* Hypothesis 1: Sales very significanly by product and season

* Hypothesis 2: Certain stores maintain consistently higher performance. 

* Validation Steps:
- Visualise total sales by month and product. 
- compare performance between stores. 
- build regression model and evaluate accuracy (MAE/MSE/R)


## Project Plan
* Combine setup, date import and cleaning (DAys 1-3) 
Train a basic regression model (Day 4) 
Create dashboards and polish README (DAY 5)

### Tools And Libraries 
-Python 3 
- Pandas, Numpy 
- Matplotlib, Seaborn 
- Scikit-learn 
- Power BI 
- VS Code + Github


## The rationale to map the business requirements to the Data Visualisations
*This section links business questions to Powr Bi 
Business Question                          Visualisation                       insights 
Sales trends over time                     line chart                        identify yearly /seasonal growth 
Category & segments performance             Donut * Bar chats               Compare contribution by category 
Regional sales                              Map or bar chat                  Identify high-performing regions 
Forcasting                                  line chart with prediction        Estimate future sales
Top product/ customers                      Table or column chart             Spot best-sellers  


## Analysis techniques used
* Descriptive analysis: Identify trends and summary statistics. 
* Correlation analysis: Check relations between numerical variables. 
* Regression modeling: Predict sales and evaluate performance using MAE,MSE,R". 


### Power BI Visualisations   
 - A Power BI dashboard was created to explore sales performance by year, category and region. visuals included:
 - Line chart for yearly sales trends 
 -Donut Chart for catgory performance 
 -Bar chart for regional and product comparisons
 Due to techinal and system lag, the final dashboard build was not possible to summit. However, the full design workflow was demostrated sucessfully, including data connetion, visual selection and layout prepation. 

## Ethical considerations
* No personal or sentive custome data was included.
* Data was publicaly available on Kaggle and anoymised. 
* All sources have been credited appropriately. 

## Dashboard Design
* The powerdashboiard was created to explore sales performance by year, category and region. visuals included 
line chart
donut and bar chart for regional and product comparisons however, due to technical and system lag, the final dashboard build could not be included. 

## Unfixed Bugs
* No majorr unresolved issues 
* Minor lag encounted in power BI when working with visuals on large dataset. 
## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Deployment
### Heroku

The project is designed for local anaysis and dashboard creation using Power Bi. A heroku disployment section is included as a reference to demonstrate understanding of stand deployment workflows. 


## Main Data Analysis Libraries
* Python 3 
Pandas, numpy 
Matplotlib, seaborn 
Scikit-learn 
Power Bi 
VS code and Github.


## Credits 

* Thanks to Mo for helping me clean up my system and stay on track despite performance issues that caused lag during Power BI use. 
Assistance was also taken from chatGPT (OpenAI) for writing support , structure guidance and proofreading of this README>
Some delays in sumission occurred due to technical issues and system lag while working with Power BI. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The dataset visuals were created with Power Bi and python notebooks 
- The images and icon used in the documentation were sourced from open-source and educational resources. 


## Acknowledgements (optional)
* Thanks to Mo and Emma for supporting me to complete this project.

## Project Summary 
This project provided valuable hands-on experice in data cleaning, exploratory analysis and dashboard creation. Despite techinical delays , the key objectives were achieved - developing insights into sales, trends, category performance and regional patterns while strengthening practical Power BI and Python skills. 

