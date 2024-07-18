# Spam Detection Project

This project aims to detect spam emails using various machine learning models. The dataset used for this project contains features extracted from email texts, and several classifiers are trained and evaluated to compare their performance.

## Dataset

The dataset used in this project is spam.csv, which contains the following columns:

- make, address, all, 3d, our, over, remove, internet, order, mail, ... (and many more features)
- cap_avg, cap_long, cap_total: Features related to capitalization in the email
- Class: The target variable indicating whether an email is spam or ham

## Project Structure

The project consists of a Jupyter notebook Project_Assignment_2_Statistics.ipynb which contains the following sections:

1. *Importing Libraries*: Importing necessary libraries such as pandas, numpy, matplotlib, and sklearn.
2. *Data Loading and Exploration*: Loading the spam.csv file and performing initial exploration to understand the data.
3. *Data Preprocessing*:
    - Extracting dependent and independent variables.
    - Splitting the dataset into training and test sets.
    - Feature scaling using StandardScaler.
4. *Model Training and Evaluation*:
    - *Voting Classifier*: Combining multiple classifiers using a voting mechanism.
    - *AdaBoost Classifier*: Using decision trees as base classifiers in an AdaBoost ensemble.
    - *Random Forest Classifier*: Training a random forest model.
5. *Task Reporting*:
    - Comparing accuracies of different models.
    - Studying the impact of training sample size on the accuracies of the models.
6. *Visualization*: Plotting graphs to visualize the accuracy percentages versus training sizes.

## How to Run

To run this project, follow these steps:

1. Clone the repository.
2. Ensure you have all the necessary libraries installed. You can install the required libraries using:
    ```bash
    pip install pandas numpy matplotlib scikit-learn
    ```
    
3. Open the Jupyter notebook:
    ```bash
    jupyter notebook Project_Assignment_2_Statistics.ipynb
    ```
    
4. Run all the cells in the notebook to execute the code and see the results.

## Results

The project compares the performance of different classifiers and analyzes how the size of the training dataset affects the accuracy of the models. The notebook includes detailed results and visualizations for these comparisons.

## Conclusion

This project demonstrates the process of building and evaluating machine learning models for spam detection. By comparing different models and analyzing their performance, it provides insights into the effectiveness of various classification techniques for this task.

## Contact

For any questions or feedback, please contact Kunal Singh at kunalsingh974@gmail.com.
