# README Template

Below is a template provided for use when building your README file for students.

# Clothing Reviews Recommendation Model

This project aims to build a machine learning model that predicts whether a customer will recommend a clothing product based on their review and other attributes. The dataset consists of anonymized clothing reviews with various features such as age, review text, and feedback count.

## Getting Started

Instructions for how to get a copy of the project running on your local machine.
Get the repo : 

git clone https://github.com/OmarMohamed7/udacity_pipeline_project
cd clothing-reviews

Load the data: 
import pandas as pd
df = pd.read_csv("clothing_reviews.csv")
df.info()

Run Tests: 

### Dependencies

```
- pandas
- numpy 
- (scikit-learn) 
- matplotlib 
- seaborn
```

### Installation

```
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Testing

pytest test_model.py


### Break Down Tests

```
Data Preprocessing Test: Ensures no missing values and correct data types.

Model Performance Test: Evaluates accuracy, precision, and recall of the model.
```

## Project Instructions

The goal of this project is to build a binary classification model using machine learning techniques to predict customer recommendations.

## Built With

* Pandas - Data manipulation

* Scikit-Learn - Machine learning models

* Matplotlib - Data visualization

* Seaborn - Statistical data visualization


## License

This project is licensed under the MIT License - see the LICENSE file for details.
