# HR-Analysis-Model-Python-

HR analytics is revolutionising the way human resources departments operate, leading to higher efficiency and better results overall. Human resources has been using analytics for years. However, the collection, processing and analysis of data has been largely manual, and given the nature of human resources dynamics and HR KPIs, the approach has been constraining HR. Therefore, it is surprising that HR departments woke up to the utility of machine learning so late in the game. Here is an opportunity to try predictive analytics in identifying the employees most likely to get promoted.
Here the data set consist of various independent related to the employees and the target variable is 'is_promoted'. so here the objective is to make a ML model which can cate these variables as input and give a prediction if the employee will be promoted or not.


# Data Reading and Data Analysis

on reading the data in python notebook with panda libraries and checking for the different variables. The variables are:

'no_of_trainings', 'age', 'length_of_service', 'avg_training_score', 'previous_year_rating', 'KPIs_met >80%', 'awards_won?', 'department', 'region', 'education', 'gender', 'recruitment_channel','is_promoted'
                 
Then Sorting the variables in continuous and catehorical columns

continouscol = ['no_of_trainings', 'age', 'length_of_service', 'avg_training_score', 'previous_year_rating', 'KPIs_met >80%',
                 'awards_won?']
                 
categoricalcol = ['department', 'region', 'education', 'gender', 'recruitment_channel','is_promoted'] 
