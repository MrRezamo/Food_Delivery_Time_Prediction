# Delivery Time Prediction Model

## Project Overview

This project aims to predict the delivery time for a logistics company using various input features such as the age and ratings of the delivery person, type of order, type of vehicle used, and the distance of the delivery.

## Data Description

The dataset contains the following columns:

- `delivery_person_age`: Age of the delivery person.
- `delivery_person_ratings`: Ratings received by the delivery person.
- `type_of_order`: The category of the order (e.g., Meal, Snack, Drinks).
- `type_of_vehicle`: The type of vehicle used for the delivery (e.g., Scooter, Motorcycle).
- `distance`: The distance of the delivery from the pickup point.
- `time_taken(min)`: The time taken for the delivery in minutes (target variable).

## Modeling

Several models were tested, with a focus on a neural network due to the complex nature of the dataset. The final model architecture included dense layers with dropout and L2 regularization to prevent overfitting.

## Results

The neural network model achieved a validation MSE of 68.21 and a validation MAE of 6.41, indicating an average error of 6.41 minutes from the actual delivery times.

## Conclusions

The project provided valuable insights into factors influencing delivery times and demonstrated the use of neural networks in predicting such outcomes. Future work may explore more complex models and additional data to improve accuracy.

## How to Use

1. Clone the repository to your local machine.
2. Install required dependencies as listed in `requirements.txt`.
3. Run the Jupyter Notebooks to see the analysis and model training process.

## Dependencies

- Python 3
- NumPy
- Pandas
- Scikit-Learn
- Keras/TensorFlow

## Contact

For any additional questions or feedback, please contact the repository owner.
