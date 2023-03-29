# MLP-depth-hypothesis-experiment
**Testing the "Depth Hypothesis" on MLPClassifier**

This repository contains code for testing the "Depth Hypothesis" with an MLPClassifier on the Titanic dataset. The hypothesis is that increasing the depth of a neural network (i.e., increasing the number of hidden layers) can lead to improved accuracy on a classification task.
Dataset

The Titanic dataset contains information about the passengers of the Titanic, including features such as passenger ID, ticket class, name, age, gender, number of siblings and spouses, number of parents and children, ticket number, fare, cabin number, and port of embarkation. The target variable is whether the passenger survived the sinking of the Titanic (1 = Yes, 0 = No).

**Dependencies**
    • pandas
    • numpy
    • matplotlib
    • seaborn
    • scikit-learn
    
**Usage**
    1. Clone the repository to your local machine:
    
       git clone https://github.com/your-username/MLP_depth hypothesis.git

    2. Navigate to the repository directory:
    
       cd titanic-depth-hypothesis

    3. Run the Jupyter notebook:
    
      jupyter notebook MLP_depth hypothesis.ipynb
      
    4. Follow the instructions in the notebook to run the code.
    
**Results**

The initial MLP classifier had an accuracy of 0.82, which indicates decent performance, but there is still room for improvement. The fine-tuned MLP classifier had a slightly better accuracy of 0.83, which suggests that increasing the depth of a neural network can lead to improved accuracy on a classification task.

**Some potential areas for further improvement include:**

    • Feature engineering: Creating new features or combining existing features to better capture the underlying relationships in the data.
    • Hyperparameter tuning: Experimenting with different hyperparameters of the MLPClassifier to see if further improvements can be made.
    • Trying other machine learning algorithms: Testing the performance of other machine learning algorithms on the dataset to see if they can outperform       the MLPClassifier.
    


