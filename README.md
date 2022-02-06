# Neural Network Charity Analysis

## The purpose of this analysis was to create a Neural Network Model to analyze and help predict which organizations would make good investment opportunities. 

## Project Overview:
1. Use preprocessing to prepare the data for a neural network model
2. Compile, train, and evaluate the model
3. Optimize the model


## Resources
- Source of data: [charity_data.csv](https://github.com/mthalken/Neural_Network_Charity_Analysis/blob/main/data/charity_data.csv)
- Software: tensorflow 2.7.0, scikit-learn 1.0.2, Python 3.7.10, Conda 4.10.3, Jupyter Notebook 6.3.0, Visual Studio Code 1.60.2
- Please see the preprocessing and training code [here](https://github.com/mthalken/Neural_Network_Charity_Analysis/blob/main/AlphabetSoupCharity.ipynb).
- Please see the optimized code [here](https://github.com/mthalken/Neural_Network_Charity_Analysis/blob/main/AlphabetSoupCharity_Optimization.ipynb).

## Results 
### Data Preprocessing
 - Target columns: IS_SUCCESSFUL 
 - Dropped columns: EIN and NAME 
 - Featured columns: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT

### Compiling, Training, and Evaluating the Model
 - The first model we ran we started with 2 hidden layers at 80 and 30 neurons respectively, with the activation function of ReLu for the hidden layers and Sigmoid for the output layer. 
     - The results of the first model was an accuracy score of 72.6% and a loss of 55.4%. 
![png](https://github.com/mthalken/Neural_Network_Charity_Analysis/blob/main/images/model_one.png)
    
    - After several different attempts to optimize the model we found the following resulted in the best accuracy score:
        - Created binning for the ASK_AMT column
        - Increased the hidden layers 3 at to 80, 50, and 30 neurons respectively
        - The results produced an accuracy score of 72.6% and a loss of 58.1%. The training accuracy did show a promising accurance score of 74.6% and a loss of 52.3%. 
![png](https://github.com/mthalken/Neural_Network_Charity_Analysis/blob/main/images/model_three.png)

## Summary




image link: ![png](link)
clink link: [here](link)
