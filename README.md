# SC1015-Project-Video-Game
## About:
This is a Mini Project for SC1015 (Introduction to Data Science and Artificial Intelligence). In this project, our topic will be on how different variables in video game are affecting the sales. We will be focusing year from 1980 to 2016. Please click onto the following detail to view our data code in order:
1. [Data Preparation and Cleaning](https://github.com/RuiLinnnn/SC1015-Project-Video-Game/blob/main/Data%20Preparation%20and%20Cleaning.ipynb)
2. [Exploratory Data Analysis](https://github.com/RuiLinnnn/SC1015-Project-Video-Game/blob/main/Exploratory%20Data%20Analysis.ipynb)
3. Machine Learning Techniques
   1. [Naive Bayes Classification](https://github.com/RuiLinnnn/SC1015-Project-Video-Game/blob/main/Naive%20Bayes%20Classification.ipynb)
   2. [Linear Regression](https://github.com/RuiLinnnn/SC1015-Project-Video-Game/blob/main/Linear%20Regression.ipynb)
   3. [Clustering](https://github.com/RuiLinnnn/SC1015-Project-Video-Game/blob/main/Clustering.ipynb)
   4. [Decision Tree and Random Forest Classification](https://github.com/RuiLinnnn/SC1015-Project-Video-Game/blob/main/Decision%20Tree%20%26%20Random%20Forest%20Classification.ipynb)
* Other Information: [Dataset](https://github.com/RuiLinnnn/SC1015-Project-Video-Game/tree/main/Dataset)
## Problem:
* Main Problem: Which genre will earn more in the future?
* Subproblem:
  1. How does the genre affect the sales among all countries?
  2. How does the platform affect the sales?
  3. How does the publisher affect the game sales?
## Models Used:
1. **Naive Bayes Classification**: To predict the class labels of instances based on their feature value.
   * Accuracy in test dataset: 12%
2. **Linear Regression**: To predict the relationship in total count vs total sale in each genre.
   * Explained Variance(R^2) in test dataset: 0.989
   * Mean Squared Error (MSE) in test dataset: 57746.016
3. **Clustering**: Clustering the similar data point together based on sale into 3 cluster to see which genre has the highest mean global sales.
   1. Lowest Sales
   2. Middle Sales
   3. Highest Sales (Total 9 genres in this cluster)
4. **Decision Tree and Forest Classification**: 
   1. Decision Tree Classification: Used to classify which genre has global sales that is above 0.54 and below 0.54.
      * Accuracy in test dataset: 41%
   2. Forest Classification: Used to verify with the accuracy of the model.
      * Accuracy in test dataset has increased to 45%
## Conclusion:
* From the models, Role playing has consistently high sales over the year. Therefore, it will have the highest chances of earning more sales in the future.
* Action, Sports and Misc have the highest sales among all the countries.
* PS2, X360 and PS3 have the most sales.
* Nintendo, Electronic and Arts Activision have earned the most revenue from 1980 to 2016.
## What did we learn:
* Handling imbalanced dataset by setting the class weight to balance
* Naive Bayes Classification
* Clustering
## Contributors:
| Team Members | Work |
| -------- | -------- |
| Chen RuiLin | Data Preparation, Linear Regression, Clustering, Decision Tree and Random Forest Classification, Github Document |
| Balaji Abarnasri | Exploratory Data Analysis, Naive Bayes Classification, Presentation |
| Li Yujia | Exploratory Data Analysis, Presentation |

## References:
* Video Game Sales dataset from [Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales). Accessed in 2024
* Reuters. (2007, August 10). *Nintendo 2006/07 profit jumps, sees further growth*. <https://www.reuters.com/article/idUST291144/>
* Geeksforgeeks. (2024, Mar 01). *Naive Bayes Classifiers* <https://www.geeksforgeeks.org/naive-bayes-classifiers/>
* Geeksforgeeks. (2024, Mar 20). *Clustering in Machine Learning* <https://www.geeksforgeeks.org/clustering-in-machine-learning/>
* Scikit Learn. (n.d). *2.3. Clustering* <https://scikit-learn.org/stable/modules/clustering.html>
