
# Singapore Resale Flat Prices Prediction

This project aims to develop and deploy a machine learning model that predicts the resale prices of flats in Singapore. The model will use historical data of resale flat transactions as the input, and output the estimated resale value of a flat. The model will be integrated into a user-friendly web application that can assist both potential buyers and sellers in making informed decisions about the resale market.


## Requirements
This project requires the following:

- Python 3.8 or higher
- Scikit-learn 0.24 or higher
- streamlit 1.1 or higher
- Pandas 1.2 or higher
- Numpy 1.19 or higher
## Installation

Install libraries to run this project

```bash
  pip install scikit-learn
  pip install pandas
  pip install numpy
  pip install streamlit
```
    
## Roadmap

- Get the data from the source - https://beta.data.gov.sg/collections/189/view.

- Cleaning the data and dealing with data types.

- Feature engineering to increase the accuracy of the model.
- Building and training the model.
- Creating the user friendly web page to get the features and show the predicted resale price.


## Explanation

- Firstly get the data from the source, which is a collection of datasets on the resale prices of flats in Singapore from 1990 to till date. The data can be downloaded from [this link](https://www.analyticsvidhya.com/blog/2021/04/steps-to-complete-a-machine-learning-project/).
- The process moves to cleaning the data and deal with data types. This involves checking for missing values, outliers, duplicates, and errors in the data. It also involves converting categorical variables into numerical ones, such as using one-hot encoding or label encoding. Additionally, it involves scaling or normalizing the numerical variables to have similar ranges and distributions [resale_data.ipynb](https://github.com/HemachandarAravamuthan/Singapore_Flat_ResalePrices_Predicting/blob/main/resale_data.ipynb).
- Then, performed feature engineering to increase the accuracy of the model. This involves creating new features from existing ones, such as using polynomial features, interaction terms, or domain knowledge. It also involves selecting the most relevant features for the model, such as using correlation analysis, feature importance, or dimensionality reduction techniques.
- After that, built and trained the model. This involves choosing a suitable machine learning algorithm for the regression problem, such as linear regression, decision tree, or random forest. Moreover, it involves evaluating the performance of the model, such as using cross-validation, mean squared error, or R-squared score.
- Lastly, created a user-friendly web page to get the features and show the predicted resale price. This involves using a web framework, such as streamlit, to create the front-end and back-end of the web application. It also involves creating a user interface, such as using streamlit components, to design the layout and style of the web page.

## Screenshots

Initial app layout
![App layout](https://github.com/MdAarif360/DS_Singapore-Resale-Flat-Prices-Predicting/blob/15dfe320c284b3266a9da8cd3032ae953285cb59/assets/Input.png)



Web page with predicted result
![Result](https://github.com/MdAarif360/DS_Singapore-Resale-Flat-Prices-Predicting/blob/53a2064e60c08324a5c825b03120b0160a4c57da/assets/Output.png)
## Contact
