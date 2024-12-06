# Indian House Price Prediction

This project aims to predict house prices in India using machine learning, specifically the CatBoostRegressor model. The dataset used contains various features of houses, including area, number of bedrooms, bathrooms, location, and amenities.

## Project Structure

- `house_cleaned.csv`: The dataset containing house information.
- `notebook.ipynb`: The Jupyter Notebook containing the data cleaning, analysis, and model building steps.
- `README.md`: This file.

## Steps Involved

1. **Data Cleaning:**
   - Handling missing values in columns like `floorNum`, `facing`, `nearbyLocations`, `furnishDetails`, `features`, and `rating`.
   - Removing irrelevant columns like `price_per_sqft`, `property_name`, `property_type`, `areaWithType`, `description`, and `address`.

2. **Data Analysis:**
   - Exploring the distribution of the target variable (price).
   - Analyzing quantitative features using box plots and scatter plots.
   - Identifying and handling outliers using the IQR method.
   - Analyzing categorical features using value counts and box plots.

3. **Feature Engineering:**
   - Transforming the `society` column into two categories: `independent` and `not independent`.
   - Grouping infrequent values in the `agePossession` column.

4. **Modeling:**
   - Splitting the data into training, validation, and testing sets.
   - Scaling numerical features using MinMaxScaler.
   - Training a CatBoostRegressor model with optimized hyperparameters.
   - Evaluating the model using MAE and R^2 metrics.

## Results

- The optimized CatBoostRegressor model achieved a high R^2 score on both the training and test sets, indicating good predictive performance.
- The MAE metric provides insight into the average prediction error in the same units as the target variable (price).

## Usage

1. Clone this repository.
2. Install the required libraries:
3. 3. Run the `notebook.ipynb` file in Google Colab or a Jupyter Notebook environment.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.
