# Clothing Fit Prediction with Machine Learning

## Overview
This project focuses on developing a machine learning model to predict clothing fit based on user ratings, aiming to bridge the gap between customer expectations and product offerings in the e-commerce domain. The dataset comprises over 300,000 samples of users, items, and transactions.

## Data Preprocessing
Data preprocessing involved handling missing data in user demographics, item details, and ratings using forward fill (ffill) method.

## Exploratory Data Analysis (EDA)
- Visualized the distribution of user ratings.
  - 120,000 users gave a rating of 10 (indicating the best fit).
  - 55,000 users gave a rating of 8.
  - 10,000 users gave a rating of 6.
  - 5,000 users gave a rating of 4.
  - A negligible number of users gave a rating of 2.

- Explored the monthly distribution of user ratings.
  - Identified November as the highest-rated month with around 10,000 average ratings.

## Model Development
- Utilized Logistic Regression initially, achieving a 75% accuracy.
- Adopted the Random Forest approach, improving accuracy to 82%.
- Concluded that clothing deliveries meet user expectations 82% of the time.

## Importance of Prediction
Improving the prediction of clothing fit has potential benefits, including higher customer satisfaction, reduced returns, and enhanced inventory management in the e-commerce sector.

## Project Goals
- Enhance customer satisfaction in e-commerce by predicting clothing fit accurately.
- Reduce return rates and associated costs.
- Improve decision-making for inventory management.

## Conclusion
This project demonstrates the practical application of machine learning models in the e-commerce industry, showcasing the impact on customer satisfaction and operational efficiency. The success of the Random Forest model emphasizes the potential for advanced predictive analytics to benefit both customers and businesses.

Feel free to explore the code and findings in this repository to gain insights into the clothing fit prediction model. Your feedback and contributions are welcome!
