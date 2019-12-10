## To Be Or Not To Be

This project accomplishes the following<br>

1. Set up a data science project structure in a new git repository in your GitHub account<br>
2. Download the Shakespeare plays dataset from https://www.kaggle.com/kingburrito666/shakespeare-plays<br>
3. Load the data set into panda data frames<br>
4. Formulate one or two ideas on how feature engineering would help the data set to establish additional value using exploratory data analysis<br>
5. Build one or more classification models to determine the player using the other columns as features<br>
6. Document your process and results<br>
7. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub<br>

## Motivation 

We will try to predict the player of a Shakespear play based on the Play, PlayerLinenumber, Act, Scene, and Line.<br>
A Random Forest classifier and a Decision Tree Classifier will be compared to see if Random Forest tradeoffs are worth any extra accuray at scale

## Results

The accuracy of the decision tree classifier at 78.7% is very close to the random forest classifier at 77.1%.<br>
This means the decision tree classifier is the better choice of model because it scales well.<br><br>
Dropping the intuitevely least usefull attribute, PlayerLinenumber,sWe see that the classifiers loses about 7% accuracy without the PlayerLinenumber column. This isn't huge, but the extra accuracy could be valuable depending on the application.<br>

