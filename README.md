# NYC-Airbnb-Price-Outlier-Removal

This project aims to clean and preprocess Airbnb listing data for New York City by removing outliers based on price per night. The goal is to provide a cleaner and more focused dataset for further analysis or modeling.

## Dataset

The dataset used for this project is the Airbnb New York City dataset, which contains information about Airbnb listings in NYC.

## Methodology

1. The original dataset is loaded into a Pandas DataFrame.

2. Percentiles are used to define upper and lower limits for price per night, with the 10th and 90th percentiles chosen to determine the range.

3. Rows with prices outside the defined percentile range are filtered out, creating a new dataset without outliers.

4. The filtered dataset is saved to a new CSV file.

## Usage

You can use the filtered dataset for your analysis or modeling purposes. The cleaned data should provide a more accurate representation of Airbnb listings in NYC without the influence of extreme price outliers.

## How to Run

To run the outlier removal process, follow these steps:

1. Clone this repository to your local machine.

2. Install the required Python libraries, such as Pandas.

3. Replace the placeholder with the path to your Airbnb NYC dataset.

4. Run the Python script to perform the outlier removal.

5. Find the cleaned dataset in the project directory.
