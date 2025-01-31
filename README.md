📌 Housing Price Prediction using Linear Regression

📖 Project Overview

This project builds a Linear Regression model to predict house prices based on various housing attributes. The dataset contains information such as the area, number of bedrooms, bathrooms, parking spaces, and additional features like air conditioning and furnishing status. The goal is to improve prediction accuracy and provide insights into house pricing.

📊 Dataset Information

Source: Housing dataset from GitHub

Number of Entries: 545

Features:

area: Square footage of the house

bedrooms, bathrooms, stories

parking, basement, guestroom

hotwaterheating, airconditioning

prefarea: Whether the house is in a preferred area

furnishingstatus: Unfurnished, semi-furnished, or furnished

Target Variable: price

🔧 Model Implementation

The model follows these key steps:

Data Cleaning & Preprocessing:

Removed irrelevant columns (id, duplicate stories.1)

Converted categorical variables (furnishingstatus) to numerical format

Handled missing values

Standardized features for better performance

Feature Engineering:

Created interaction features like area * parking

Applied transformations to improve model stability

Model Training & Evaluation:

Used LinearRegression() from sklearn

Splitted data into 80% training, 20% testing

Achieved an R² score of ~0.64

📈 Performance Metrics

Mean Squared Error (MSE): Measures the average squared difference between actual and predicted prices.

R² Score: Indicates how well the model explains variance in the target variable. The goal is to improve this score to 0.8+ using:

Feature selection & engineering

Polynomial regression

Hyperparameter tuning

Alternative models like Random Forest or Gradient Boosting

🏃 How to Run the Project

1️⃣ Install Dependencies

pip install pandas numpy seaborn matplotlib scikit-learn

2️⃣ Run the Script

python housing_price_model.py

🚀 Future Improvements

✅ Try Polynomial Regression for better curve fitting✅ Use Random Forest & Gradient Boosting for higher accuracy✅ Apply Feature Selection to remove multicollinearity✅ Perform Hyperparameter Tuning to optimize model performance

🤝 Contributing

If you’d like to contribute, feel free to fork the repository and submit a pull request.

Happy coding! 😊