# Flight Delay Analysis Package

This R package provides a comprehensive framework for analyzing and predicting flight delays. It integrates data from flight schedules and weather conditions to model the likelihood of delays. The package includes tools for data preprocessing, model training, prediction, and visualization.

## Key Features

- **Data Integration**: Combines flight data with weather conditions to enhance predictive accuracy.
- **Model Training**: Utilizes logistic regression to predict flight delays based on historical data.
- **Data Visualization**: Offers various plots to visualize delay rates by carrier, hour of day, precipitation, wind speed, and more.
- **Menu-Driven Interface**: Provides an interactive menu for users to explore different aspects of flight delay analysis.

## Installation

To install this package, you can use the following command:
install.packages(c("tidyverse", "tidymodels", "nycflights13", "ggplot2", "vip", "caret"))

## Usage

1. Load the necessary libraries and data.
2. Run the `menu_choice` loop to interact with the package's features.


## Menu Options

The menu-driven interface offers the following options:

1. **View Overall Model Accuracy**: Displays the confusion matrix and accuracy of the model.
2. **View Impact of Weather Conditions on Delays**: Visualizes feature importance for weather conditions.
3. **View Carrier with Highest Delay Rate**: Displays the carrier with the highest average delay rate.
4. **View Delay Rates by Departure Hour**: Plots delay rates by hour of day.
5. **View Delay Rates by Origin Airport and Temperature**: Visualizes delay rates by origin airport with average temperature.
6. **Compare Actual vs Predicted Delay Rates**: Compares actual and predicted delay rates.
7. **View Delay Rate by Precipitation**: Plots delay rates by precipitation.
8. **View Impact of Wind Speed on Delay Rate**: Visualizes delay rates by wind speed.
9. **View Delay Rate by Month**: Plots delay rates by month.
10. **View Delay Rate by Carrier and Hour of Day**: Displays delay rates by carrier and hour of day.
11. **Exit**: Exits the menu.

## Contributing

Contributions are welcome! Please submit pull requests or issues to improve the package.

## License

This package is licensed under the MIT License.

## Acknowledgments

This package utilizes data from the `nycflights13` package for flight information and integrates weather data for comprehensive analysis.

---

### Example Use Cases

- **Analyzing Delay Patterns**: Use the menu options to explore how different factors (e.g., weather, time of day) affect flight delays.
- **Predicting Delays**: Train and evaluate the logistic regression model to predict flight delays based on historical data.

### Known Issues

- Ensure that all necessary dependencies are installed before running the package.
- The package assumes that the data is correctly formatted and does not handle incorrect input formats.

### Future Development

- Expand the model to include additional predictors (e.g., air traffic control delays).
- Integrate real-time weather data for more accurate predictions.

