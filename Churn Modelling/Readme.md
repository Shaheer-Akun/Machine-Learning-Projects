#### Churn Customer Data

#### Supervised Classification Problem

#### Requirements
* Python
* Keras
* Scikit Learn
* Numpy
* Pandas
* Theano
* TensorFlow


#### Approach Taken 
* I downloaded dataset from <a href = 'https://data.world/'>Data.world</a>
* After inspecting Dataset, I found columns name inconsistent, so rename some columns.
* Remove some duplicate columns.
  * For verrification of duplicacy, I used Tableau adhoc - ab testing and python assert statement.
* Checked the effect of all categorical variable using Tableau and performed <b> Chi-square test</b> to verify statistical significance.
* Checked the distribution of numerical data and found skewed data.
* Used boxcox1p transformation.
* Class was imbalanced so used stratify in splitting.
* Checked outlier using functions and box plots.
* After performing splitting and Standardization, I checked accuracy of different algorithms.
* Implemented ANN using Keras
* Performed GridSearch for HyperParameter Tuning and implemented with selected parameters on Test set.

#### Result
* RandomForest = 80% accuracy
* Artificial Neural Network - 84% accuracy
