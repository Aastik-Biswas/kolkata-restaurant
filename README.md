# Zomato Kolkata Restaurant Data Analysis

## Project Overview
This is a  exploratory data analysis project based on a Zomato restaurant dataset for Kolkata.

The project focuses on understanding restaurant distribution, cuisine popularity, pricing, ratings, reviews, and service features. It also includes a simple Linear Regression model that estimates the average restaurant cost.

## Dataset
The dataset contains 4,923 restaurant records and 19 columns.

Important fields include:
- Restaurant name
- Area
- Cuisines
- Dinner and delivery ratings
- Dinner and delivery review counts
- Home delivery
- Takeaway
- Indoor seating
- Veg-only status
- Average cost

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Work Performed
1. Loaded and inspected the dataset.
2. Removed duplicate records.
3. Converted rating columns to numeric values.
4. Handled missing values.
5. Generated descriptive statistics.
6. Identified the areas with the most restaurants.
7. Identified the most common cuisines.
8. Visualized restaurant cost distribution.
9. Compared service features such as delivery and takeaway.
10. Studied the relationship between dinner rating and restaurant cost.
11. Listed highly rated restaurants with a minimum review threshold.
12. Built a simple Linear Regression model for average-cost prediction.
13. Evaluated the model using Mean Absolute Error and R-squared.

## How to Run in Google Colab
1. Open Google Colab.
2. Upload `Zomato_Kolkata_Restaurant_Analysis.ipynb`.
3. Run the notebook from the first cell.
4. When prompted, upload `Zomato_Kolkata_Restaurants.csv`.
5. Run all remaining cells in order.

## Machine Learning
The model uses:
- Dinner rating
- Dinner reviews
- Delivery rating
- Delivery reviews
- Home-delivery flag
- Takeaway flag
- Indoor-seating flag
- Veg-only flag

Target:
- Average restaurant cost

The Linear Regression model is intended as a simple baseline rather than a production prediction system.

## Project Value
This project demonstrates practical use of:
- Data cleaning
- Exploratory data analysis
- Data visualization
- Feature preparation
- Regression
- Model evaluation

## Files
- `Zomato_Kolkata_Restaurant_Analysis.ipynb` - complete Colab notebook
- `Zomato_Kolkata_Restaurants.csv` - dataset
- `README_Zomato_Kolkata_Analysis.pdf` - project documentation
