## Exploratory Data Analysis in Python

### EDA
<p>Enables an in depth understanding of the dataset, defines or discards hypothesis and helps create predictive models on a solid basis.</p>

**Rule of Thumb : ** 80% time in data preparation & exploration where as 20% in actual machine learning modeling.

### EDA Process
![EDA Procoess](https://miro.medium.com/max/1400/1*ejW2uqLQ0W3lUsTBNxhxcg.png)
- **Required libraries for EDA** : Pandas, Numpy, Sklearn, Matplotlib, Seaborn
- **Understanding the big picture** : making sense of the problem at hand, thinking about the entire dataset & the meaning of the variables
  - Variable : name of the variable
  - Type : catgorical, numeric, boolean and so on
  - Context : useful information to understand the semantic space of the variable
  - Expectation : how relevant is this variable with respect to our business case at hand
  - Comments : whether or not we've any comments to make on the variable
- **Preparation** : cleaning our dataset, some of the questions one shall ask during this phase - 
  - Are there any useless or redundant variables?
  - Are there any duplicate columns?
  - Does the nomenclature make sense?
  - Are tehre any new variables we want to create?
- **Understand the variables** : to fully understand each variable using **univariate analysis**
- **Relationship between variables** : it shows the influence of one variable on the other, preferably on the target using **heatmap** as it allows us to efficiently grasp which variables are stongly correlated with each other
- **Brainstorming** : To continue with the analysis either
  - Create a report for the stakeholders
  - Do modeling
  - Further more exploration to clarify business questions

