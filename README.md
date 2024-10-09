# Weather-Forecasting-Project
The Weather Data Visualization project allows users to analyze and visualize weather data from a CSV file for multiple cities. By selecting specific cities and data columns, users can generate various types of charts, including line, bar, and pie charts. This tool is useful for comparing weather metrics across different locations and understanding trends over time.
# Table of Contents
  - [Installation](#Installation)
  - [Usage](#Usage)
  - [Features](#Features)
  - [Code Explanation](#CodeExplanation)
  - [Contributing](#Contributing)
  - [License](#License)
  - [Contact](#Contact)
# Installation
  - Ensure you have Python installed on your machine
  - Install the required libraries by running:[pip install pandas matplotlib]
  - Download the Weather_Data_CSV_File.csv and place it in your desired directory. Update the file path in the script as necessary.
# Usage
  - Open the Python script in your preferred IDE or text editor.
  - Run the script:[python your_script_name.py]
  - Follow the prompts to enter:
     - Cities you want to visualize (comma-separated)
     - Columns you want to visualize (comma-separated)
     - Chart type (pie, line, bar)
## Example Input
  - Enter the cities you want to visualize (comma-separated): Indore, Pune
  - Enter the columns you want to visualize (comma-separated): Temperature, Humidity
  - Enter the chart type (pie, line, bar): line
## 1. Temperature Over Time
![Screenshot (143)](https://github.com/user-attachments/assets/acfe543c-c9a3-4645-b630-e4576f826fd5)

## 2. Humidity Over Time
![Screenshot (145)](https://github.com/user-attachments/assets/c6e5f498-4d80-4413-925e-cc9fc5c9122e)

## 3. Wind Speed Over Time
![Screenshot (146)](https://github.com/user-attachments/assets/da2a8cc6-0451-47f6-bc07-e10ac40ae229)

# Features 
   - Interactive Visualization: Users can input cities and columns of interest for tailored data analysis.
   - Multiple Chart Types: Supports line, bar, and pie charts for diverse data representation.
   - Custom Filtering: Easily filter and visualize data for selected cities, enabling focused analysis

# Code Explanation
The main components of the script include:
   - Loading Data: The script uses pandas to load weather data from a specified CSV file.
   - Plotting Function: The plot_chart function generates plots based on user input.It filters data for selected cities and allows for different chart types:
       - Line Chart: Visualizes trends over time for selected columns.
       - Bar Chart: Compares values for different cities and columns.
       - Pie Chart: Displays proportions for a single column per city.
   - User Input: The script collects user input for cities, columns, and chart type, ensuring flexibility in data visualization

# Contributing
Contributions are welcome! Feel free to fork the repository, create a branch, and submit a pull request. Suggestions for improvements or additional features are encouraged.

# License
his project is licensed under the MIT License.

# Contact
Ajay Bhagat-[ajbt942438@gmail.com]
     
      
