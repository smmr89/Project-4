# Project 4 - Wine Quality 


## <ins>Contents Page</ins>

* [Overview](#Overview-header)
* [Methodology](#Methodology-header) 
* [Models](#Models-header)
* [Conclusion](#Conclusion-header)

## <a id="Overview-header"></a><ins>Overview</ins>

For Project 4, we undertook the challenge of classifying Red Wine into distinct categories of quality—differentiating between good and bad wine—based on a combination of physiochemical inputs and sensory output variables, leveraging machine learning and other technologies. 

## <a id="Methodology-header"></a><ins>Methodology</ins>

* Imported the Wine Dataset into Google Colab using PySpark.
* Leveraged the flexibility of Pandas to execute SQL queries on the imported dataset.
* Recognized the importance of enhancing the robustness of the analysis.
* Standardized the dataset to ensure consistency and accuracy in subsequent analytical steps.

## Technologies Used
- Scikit-learn: Utilized for implementing machine learning models.
- Python Pandas: Employed for data manipulation and analysis.
- Google Colab: Leveraged as the platform for executing the project.
- PySpark: Used for efficient data import into Google Colab.
- pyspark.spl : Employed for enhanced data querying capabilities.
- Nueral Network Deep Learning with Keras Tuner: Applied for developing sophisticated neural network models.


## <a id="Models-header"></a><ins>Models</ins>

Our machine learning pipeline comprised several sophisticated models, each carefully selected to optimize predictive performance:

-Logistic Regression Classifier with the default lbfgs solver: Leveraged the default lbfgs solver for logistic regression.

-Logistic Regression Classifier with the liblinear solver: Implemented logistic regression using the liblinear solver.

-Logistic Regression Classifier with the default lbfgs solver and integrated RandomOverSampler: Utilized logistic regression with the default lbfgs solver, integrated with RandomOverSampler to handle class imbalance.

-Random Forest Classifier: Employed for its ensemble learning capabilities.

-Support Vector Classifier: Utilized for its effectiveness in high-dimensional spaces.

-Nueral Network Deep Learning with Keras Tuner: Applied advanced neural network techniques, fine-tuned with Keras Tuner for optimal performance.

The primary project objective was to apply diverse machine learning methodologies to a Red wine dataset, evaluating the effectiveness of different techniques in terms of model accuracy.

## <a id="Conclusion-header"></a><ins>Conclusion</ins>


In conclusion, our machine learning pipeline for classifying Red Wine quality comprised a diverse set of sophisticated models, each meticulously chosen to optimize predictive performance. We explored various techniques, including logistic regression with different solvers, Random Forest, Support Vector Classifier, and Neural Network Deep Learning with Keras Tuner. The primary goal was to assess the effectiveness of these methodologies on a Red wine dataset and optimize model accuracy.

Throughout the project, it became evident that the dataset exhibited significant class imbalance. While we addressed this challenge in some models by integrating RandomOverSampler, the impact on the overall performance was notable. The models' predictive accuracy could have been further refined, especially in terms of handling imbalanced data, potentially leading to enhanced results.

One avenue for improvement involves a more in-depth analysis of the confusion matrix, incorporating techniques such as interquartile range assessment. This could provide valuable insights into model performance, particularly in correctly identifying instances of both good and bad wine quality. By refining our approach to handling imbalanced data and leveraging additional evaluation metrics, we have the opportunity to enhance the overall robustness of our classification models for Red Wine quality.

## Dataset
Our project is powered by a dataset containing 1600 records. The dataset is focused on kaggle as:(https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009/data)

## Contributors
- Habib Rehman
- Mushfiqur Rahman
- Nev Shanmugathasan
- Mohammed Zayan

