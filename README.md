# Zomato Dataset Analysis

This project involves analyzing the Zomato dataset to gain insights into various aspects of the restaurant industry, including country-wise analysis, ratings, and currency information.

## Project Structure

The project consists of the following files:

- notebook/zomato.ipynb: Jupyter notebook containing the code for analyzing the Zomato dataset.
- data/zomato - zomato.csv: Dataset file containing restaurant information.
- data/Country-Code - Sheet1.csv: Dataset file containing country code information.
- requirements.txt - File containing the required packages for the project.

## Requirements

The project requires the following packages to be installed:

- Pandas
- Matplotlib
- Seaborn

To install these packages, you can use the following command:
    ```bash
    pip install pandas matplotlib seaborn
    ```

## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/jaywyawhare/Zomato-Data-Analysis.git
    ```

1. Navigate to the project directory:

    ```bash
    cd Zomato-Data-Analysis
    ```

1. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

1. Run the Jupyter notebook:

    ```bash
    jupyter notebook
    ```



## Results
The provided code performs the following analyses and visualizations:

- Loading the Zomato dataset and checking for missing values.
- Merging the Zomato dataset with the Country Code dataset.
- Determining the number of unique countries in the dataset and listing the country names.
- Creating a pie chart and bar chart to visualize the top three countries with the most restaurants.
- Grouping the data by aggregate rating, rating color, and rating text to obtain the rating count.
- Grouping the data by country and currency to obtain the currency count.
- Listing the countries that have online delivery available.
- Listing the countries with an aggregate rating of 0.

## Conclusion
The provided code performs basic analysis and visualization on the Zomato dataset, providing insights into restaurant information, country-wise analysis, and ratings. You can further expand upon this code to perform more in-depth analyses or customize it based on your specific requirements.

If you have any questions or need further assistance, please feel free to reach out.

*This project is a sample analysis of the Zomato dataset and serves as a starting point for further analysis and exploration.*