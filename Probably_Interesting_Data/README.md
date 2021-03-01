## Project 01: Probably Interesting Data
Pick Two datasets from [Kaggle](https://www.kaggle.com/datasets) and build an algorithm to model those datasets using mixture models.
## Algorithm
For this project, I have implemented **Kmeans clustering** algorithm which is an iterative proccess contains two phases:
* Phase One: Distribute the data points to the nearest center of K centers 
* Phase Two: Re-compute the centers by computing the means of their clusters.
This procedure is repeated until there is no further change in assignment or the number of iterations pass limit.

## Datasets
Since Kmeans algorithm can not deal with categorical data, I choose these two datasets which contain mostly numerical data.
* [Iris Species](https://www.kaggle.com/uciml/iris). I choose to demonstrate the relationship between Sepal Length and Petal Length, since they seem to be evenly distributed
* [Wine Qualities](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009). I choose to demonstrate the relationship between fixed acid and pH. Same the reason as the Iris dataset.

## Results
The results are demonstrated here:
* [Iris Species model](https://github.com/Thang-sudo/EECS_738_Machine_Learning/blob/main/Probably_Interesting_Data/Iris.ipynb)
* [Wine Quality model](https://github.com/Thang-sudo/EECS_738_Machine_Learning/blob/main/Probably_Interesting_Data/Wine_Quality.ipynb)

## Discussion
**Kmeans** algorithm is really easy to implement. However, I find it difficult to choose proper number K. In addition, bad separation can happen with data points that are similar (this can be seen in Wine Quality model).

## Reference
Bishop (2006) Pattern Recognition and Machine Learning.
