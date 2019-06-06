## Hackathon at General Assembly: Predicting Income with Limited Features
Completed this project in collaboration with Alanna Besaw, Patric Cavins, Anna Haas, and William Holder

### Background Information:
Project Management Venn Diagram:

![](https://berkonomics.com/wp-content/uploads/2015/11/goodfastcheap1-1.png)

It is difficult to complete a high-quality, cheap project quickly.  Generally, only two of the three priorities above can be set for a project.  For example, a project that is high-quality and cheap will likely take a longer time to complete.  A high-quality project can be completed fast, but it will likely be more expensive to complete.  A low-cost project can be completed fast, but it might not be as high-quality as it could be if there was more time or money put into the project. 

### Problem Statement / Goal:
Can an accurate model be built to predict the probability that a person's income is above $50,000 when the model can only be built using a limited number of features?  

We were limited to using a maximum of 20 features to build our model.  We were able to utilize various algorithms and the large dataset or the small dataset given.  Other teams were limited to either using a smaller dataset or only being able to use the random forest classifier algorithm to build their models.

We were given approximately six hours to get explore the dataset, clean the dataset, feature engineer, model, and optimize models.  We submitted our test dataset predictions at the end of the hackathon.

### Project Outline:
1. We got acquainted with the dataset, and we cleaned the dataset.
2. We conducted exploratory data analysis (EDA), and we narrowed down the number of features to 20 features.
3. We created models.
4. We evaluated our models, and we decided to use the most accurate model to generate test set predictions (which we then submitted for the competition).

### Data Dictionary:
Descriptions of the data can be found [here](http://archive.ics.uci.edu/ml/machine-learning-databases/adult/old.adult.names) and [here](http://archive.ics.uci.edu/ml/machine-learning-databases/adult/adult.names).
 
### Repository Structure:
#### Contents of the code folder:
- 1_data_cleaning_AnnaHaas.ipynb
- 2_ExploratoryDataAnalysis_AnnaHaas.ipynb
- 3_EDA_JuliaTaussig.ipynb
- 4_ModelingAndModelEvaluation.ipynb

#### Contents of the data folder:
- cheap_train_sample.csv: The smaller sample dataset (teams who had the smaller dataset limitation used this dataset to train their models)
- large_train_sample.csv: The larger sample dataset (teams who did not have to use the smaller dataset were able to use this dataset to train their models)
- train_clean_Anna1.csv: The train dataset that had the features we decided to use (Anna Haas created this clean version of the dataset for team model building)
- test_data.csv: The test dataset that had all features included
- test_clean_Anna1.csv: The test dataset that had the features we decided to use (Anna Haas created this clean version of the dataset for team model prediction generation)

### Executive Summary:
See our blog post that contains our discussion of the hackathon and an executive summary [here](https://medium.com/@julia.taussig/predicting-income-with-feature-limitation-1786c8fcb087).

### Sources:
Dave Berkus, https://berkonomics.com/wp-content/uploads/2015/11/goodfastcheap1-1.png

The data that was used for this analysis was extracted by Barry Becker from the 1994 U.S. Census Bureau database found at http://www.census.gov/ftp/pub/DES/www/welcome.html.

The data and data dictionary can be found at Kaggle’s “Adult Census Income:
Predict whether income exceeds $50K/yr based on census data” competition page: https://www.kaggle.com/uciml/adult-census-income.

Data description: http://archive.ics.uci.edu/ml/machine-learning-databases/adult/old.adult.names

Data description: http://archive.ics.uci.edu/ml/machine-learning-databases/adult/adult.names