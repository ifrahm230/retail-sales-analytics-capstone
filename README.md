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

Tools And Libraries 
-Python 3 
- Pandas, Numpy 
- Matplotlib, Seaborn 
- Scikit-learn 
- Power BI 
- VS Code + Github


## The rationale to map the business requirements to the Data Visualisations
*This section will be completed after I create my dashboard 
## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques. Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations
* Were there any data privacy, bias or fairness issues with the data?
* How did you overcome any legal or societal issues?

## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Deployment
### Heroku

* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.


## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)
* Thank the people who provided support through this project.