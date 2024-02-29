# Netflix-Movies-And-TV-Shows-Clustering




Netflix-Movies-and-TV-Shows-Clustering
AlmaBetter Capstone Project
![1_MlYDmLXuoeOLHiJoIIjsRg ](https://user-images.githubusercontent.com/113963339/213934250-58cf1d46-d11c-43dd-af89-741483388519.jpg)



## Project Overview

### Objectives:
1. Conduct Exploratory Data Analysis.
2. Understand the type of content available in different countries.
3. Analyze if Netflix is increasingly focusing on TV rather than movies in recent years.
4. Cluster similar content by matching text-based features.

### Methods used:
- Descriptive Statistics.
- Data Visualization.
- Machine Learning.

### Libraries utilized:
- NumPy and Pandas: For dataset cleaning and analysis.
- Matplotlib, Plotly, and Seaborn: For Data Visualization.
- Scikit-learn and nltk: For machine learning and clustering.

Netflix, an American subscription streaming service and production company founded in 1997, offers a library of films and television series through distribution deals and its own productions, known as Netflix Originals.

After loading the data, the project begins by observing the first and last five values to understand the dataset. Feature engineering is then conducted to extract new variables from the datetime variable `date_added`.

The cleaned data is used for Exploratory Data Analysis (EDA) to understand the dataset better and identify underlying trends.

After obtaining insights from EDA, the text data is pre-processed by removing punctuation and stop words. The filtered data is then passed through TF-IDF Vectorizer for text-based clustering.

Clusters are built using the Agglomerative clustering algorithm, with the optimal number of clusters determined to be 12 through visualization of the dendrogram.


