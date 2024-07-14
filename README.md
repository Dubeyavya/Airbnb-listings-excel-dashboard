# Airbnb Listings Dashboard Project

This repository contains the project files for the Airbnb Listings Dashboard, showcasing the entire process from data loading and cleaning to analysis and visualization.

## Project Overview

This project involves creating a comprehensive dashboard to analyze Airbnb listings data. The dashboard helps in visualizing various aspects of the data, such as room type distribution, average prices, and availability of listings.

## Loading the Data

The data is loaded into Excel from the provided dataset, which contains columns such as:

- `id`
- `name`
- `host_id`
- `host_name`
- `neighbourhood_group`
- `neighbourhood`
- `room_type`
- `price`
- `minimum_nights`
- `number_of_reviews`
- `last_review`
- `reviews_per_month`
- `calculated_host_listings_count`
- `availability_365`

## Data Cleaning

Data cleaning is an essential step to ensure accuracy and reliability. The following actions were performed:

- Removed duplicates to ensure each listing is unique.
- Handled missing values .
- Removed unnecessary columns to streamline the dataset.

## Data Analysis

With the cleaned data, various analyses were conducted to extract insights:

- **Room Type Distribution:** Analyzed the proportion of different room types.
- **Average Price by Neighbourhood Group:** Calculated the average price across different neighbourhood groups.
- **Listings Availability:** Assessed the average availability of listings throughout the year.

## Creating Pivot Tables

Pivot tables were instrumental in summarizing the data:

- Created pivot tables for `room_type`, `neighbourhood_group`, `price`, and `availability_365`.
- Linked pivot tables to slicers for dynamic data filtering.

## Visualizing the Data

Visualizations were key to making the data comprehensible:

- **Pie Chart:** Showcased the distribution of room types.
- **Bar Charts:** Displayed the average price by neighbourhood group and availability of listings.
- **Column Chart:** Highlighted the number of listings by neighbourhood.
- **Line Chart:** Illustrated reviews per month by room type.

## Interactive Dashboard

An interactive dashboard was created by linking slicers to the pivot tables and charts:

- Users can filter the data by `room_type` and `neighbourhood_group` using slicers.
- All charts update dynamically to reflect the filtered data, providing a seamless user experience.

## Result

The end product is a powerful, interactive dashboard that allows users to explore and analyze Airbnb listings data efficiently. This project not only enhanced data analysis and visualization skills but also demonstrated the importance of clear, actionable insights in decision-making.

## How to Use

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/airbnb-listings-dashboard.git](https://github.com/Dubeyavya/Airbnb-listings-excel-dashboard
    ```
2. **Open the Excel File**:
    - Open `airbnb listings excel dashboard.xlsx` in Microsoft Excel.
3. **Explore the Dashboard**:
    - Interact with the slicers and charts to analyze the data.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
