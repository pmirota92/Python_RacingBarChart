# Bar Chart Race for CO2 Emissions

## Overview
This Python script creates a bar chart race to visualize the top 15 countries with the highest CO2 emissions from 1960 to 2019. The data is read from a CSV file and is processed into an animated bar chart race using the `bar_chart_race` library.

## Demo
![Python_RacingBarChart](demo/RacingBarChart.gif)

## Requirements
Make sure you have the following Python libraries installed:
- `pandas` 
- `bar_chart_race`

You can install them using:
```bash
pip install pandas bar_chart_race
```

## How It Works
1. The script reads the CO2 emissions data from a CSV file using `pandas`.
2. The data is then passed to the `bar_chart_race` function to generate the animation.
3. The bar chart race displays the top 15 countries, with various parameters set to customize the appearance, such as:
   - **Title**: 'Top 15 Countries with Most CO2 Emissions, 1960-2019'
   - **Period**: 1960 to 2019
   - **Number of Bars**: 15
   - **Frame Size**: 6 x 5

## Usage
To run the script, ensure that the CSV file is in the correct format (semicolon `;` as delimiter) and adjust the file path in the code:
```python
dframe = pd.read_csv(file_path, delimiter=';')
```
Then, simply execute the script, and it will produce an animated bar chart of CO2 emissions over the specified period.

## Parameters
- **df**: DataFrame containing CO2 emission data.
- **title**: The title of the bar chart race.
- **n_bars**: Number of countries to display.
- **period_length**: Controls the speed of the animation.
- **steps_per_period**: The smoothness of the transition between years.
- **period_fmt**: Formats the period label, showing the year.
  
Adjust these parameters as needed to fit your dataset or preferences.
