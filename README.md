### Analysis of US Housing Market Data - [View Here](https://github.com/graceli5/PIC-16B-Final-Project.git)

_Completed in collaboration with UCLA peers during the 2023-2024 school year._

**Project**: Analyzing what factors most heavily influence US housing prices, and constructing a model to classify listing prices.
- Merged together four datasets, preformed data cleaning, and explored dimension reduciton/feature selection to prepare for modeling.
- Created in-depth Seaborn visualizations to depict trends and relationships.
- Trained and compared SVM, Logistic Regression, K Nearest Neighbors, Decision Tree, Random Forest and Max Voting Classifier models, each constructed using a Grid-Search algorithm to tune parameters and cross validation on testing data.
- Established a neural network model by tuning depth, batch size, and activation funciton, implemented confusion matrix to analyze error.

### Machine Learning Research on Music Data - [View Here](https://github.com/graceli5/UPF-work.git)

_Research work done as a UPF Music Technology Group Intern._

**Project**: Researching whether it is possible to predict when a participant is singing using correct or poor posture using only respiration sensor data.
- Created statistical summary features of respiration patterns for each note sung including data like mean, median, variance, peak spacing, range, etc.
- Constructed Scikit-Learn models (knn, random forest, logistic regression, svm) taking in these summary features and utilizing parameter tuning and cross validation to inform decision. Explored TensorFlow neural network models to produce similar predictions and compared testing accuracies.

**Project**: Exploring the accuracy with which models can predict the pitch/note a singer is at by analyzing their facial position in video data.
- Built high preforming KNN and random forest models that classified into four evenly split categories of notes using 60 facial landmarks.
- Implemented PCA dimension reduction to improve computational speed and energy, re-tested models using just 4 components and they remained similarly effective.
- Preformed univariate and bivariate feature importance analysis to attempt to identify which facial points are most indicative of pitch while one is singing.
 
