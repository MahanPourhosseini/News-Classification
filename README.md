### Problem Statement

This project represents the work undertaken as part of the Machine Learning course's midterm exam, focusing on the task of text classification. The exam specifically involved a case study related to an Iranian newspaper dataset. The primary objective was to build and evaluate text classification models to categorize newspaper articles into predefined topics accurately.

### Table of Contents

- [Exploratory Analysis](#a-exploratory-analysis)
- [Text Cleaning](#b-text-cleaning)
- [Vectorization](#c-vectorization)
- [Train and Test Split](#d-train-and-test-split)
- [Model Training](#e-model-training)
- [Conclusion](#conclusion)

### A. Exploratory Analysis

The initial step involved exploring the Iranian newspaper dataset provided for the midterm exam. This exploratory analysis aimed to gain insights into the dataset's characteristics, class distribution, and the nature of its textual content. These insights were essential in understanding the challenges and opportunities associated with the task.

### B. Text Cleaning

To ensure data quality and consistency, rigorous text cleaning procedures were applied. This included removing special characters, punctuation, and common stopwords. The objective was to prepare the text data for subsequent analysis and modeling.

### C. Vectorization

Text data was transformed into numerical vectors using two prominent techniques: TF-IDF (Term Frequency-Inverse Document Frequency) and Count Vectorization. These techniques converted the textual data from the Iranian newspaper case study into a format suitable for machine learning model training.

### D. Train and Test Split

Appropriate partitioning of the dataset into training and testing subsets was crucial for accurate model evaluation. Care was taken to maintain class balance in both the training and testing datasets. This division allowed for a comprehensive assessment of model generalization to unseen data.

### E. Model Training

The core of the midterm exam code involved training and evaluating text classification models. Various machine learning algorithms were explored, including Random Forest, Linear SVC, Logistic Regression, Decision Tree, and K-Nearest Neighbors (KNN). Model performance was assessed using accuracy as the primary evaluation metric on both training and testing datasets.

### Conclusion

This midterm exam code focused on the task of text classification within the context of an Iranian newspaper dataset. The project encompassed data exploration, text preprocessing, feature engineering, and model training. Notably, it provided an opportunity to assess the performance of different machine learning algorithms on the given task.

The exam results indicated that the Random Forest model, coupled with TF-IDF vectorization, demonstrated the highest accuracy in categorizing newspaper articles into predefined topics. This achievement highlights the potential of this approach for similar real-world applications in the domain of Iranian newspapers or text classification in general.

While this code represents a successful midterm exam submission, it's important to recognize that text classification tasks often involve ongoing refinement and exploration. Further enhancements, such as hyperparameter tuning and advanced modeling techniques, could be explored to further improve classification performance. This project serves as a valuable foundation for tackling similar natural language processing challenges in the future.
