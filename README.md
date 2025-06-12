Rainfall Prediction Project

Module 13 – Assignment 9  
This project is about predicting rainfall levels based on different weather factors like temperature, humidity, dew point, wind speed, and visibility. The main goal was to use **Linear Regression** to understand how these factors affect precipitation.



About the Dataset

The dataset used in this project is called **austin_weather.csv**, which contains daily weather records from Austin, Texas. It includes details like:

- Average temperature
- Humidity
- Dew point
- Visibility
- Wind speed
- Precipitation (in inches)

## What I Did

1. **Uploaded and Loaded the Data**  
   I started by uploading the CSV file and loading it using pandas.

2. **Cleaned the Data**  
   - Removed unnecessary columns like `Events` and `Date`.
   - Replaced values like `'T'` and `'-'` with `0.0` since they represent trace amounts or missing data.
   - Converted everything to numbers and dropped any rows with missing values.

3. **Prepared the Data for Modeling**  
   - Chose all columns except `PrecipitationSumInches` as features (X).
   - Set `PrecipitationSumInches` as the target variable (y).

4. **Split the Data**  
   - Split the dataset into training and testing sets (80% train, 20% test).

5. **Trained a Linear Regression Model**  
   - Used `LinearRegression` from `sklearn` to build the model.

6. Evaluated the Model 
   - Calculated R² score and Mean Squared Error (MSE) to see how well the model performed.

7. Plotted the Results 
   - Created a line chart comparing actual vs predicted precipitation values.
   - Also made a correlation heatmap to check relationships between features.

## Tools and Libraries Used

- Python
- pandas
- matplotlib
- seaborn
- scikit-learn

## Final Thoughts

This was a really helpful project to understand how Linear Regression works in real-life scenarios. It also showed how important it is to clean and prepare data properly before using any machine learning model.


