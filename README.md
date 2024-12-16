# Final
Data Bootcamp Final Fall24
For my final project I investigated clustering methods in multiple spotify datasets containing artist, genre and specific year information. For my prediction models I used Random Forest, Decision Tree, and SVM (support vectors machine). 
Although the precision and R^2 were mediocre to low, I learned a lot about the complexity of music data analysis, the importance of feature selection, and how different machine learning models can capture different aspects of music characteristics - with each model showing unique strengths in predicting either popularity or genre classification

The analysis focused on understanding song popularity patterns and genre classification using various machine learning approaches.

Models Implemented:
Random Forest (R² = 0.347, MSE = 310.38)
Decision Tree (R² = 0.354, MSE = 306.68)
Support Vector Machine (SVM) for genre classification
Overall accuracy: 2.48%
Strong performance in specific genres:
Rock (73% precision)
Hip Hop (63% precision)
Adult Standards (54% precision)
Key Findings:

Feature Correlations:
Strong positive correlations between:
Valence and danceability (0.559)
Energy and loudness (0.782)
Energy and popularity (0.485)
Strong negative correlations between:
Acousticness and energy (-0.749)
Acousticness and popularity (-0.573)

Clustering Analysis:
Used KMeans clustering
PCA analysis revealed 9 components needed to retain 90% variance
Identified natural groupings of songs based on audio features

Model Performance:
Tree-based models showed limited but consistent performance
SVM demonstrated specialized ability in certain genre classifications
Clustering provided insights into song similarity patterns
Although the precision and R² values were mediocre to low, I learned valuable lessons about:

The complexity of music popularity prediction
The importance of feature engineering
The challenges of multi-label classification
The value of different modeling approaches for different aspects of music analysis
The limitations of using purely audio features for popularity prediction
Tools & Technologies Used:

This project provided practical experience in handling real-world data challenges and implementing various machine learning techniques for both regression and classification tasks.
