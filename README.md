# Pandas_Numpy_Dev_Ops
This Python project focuses on data cleaning and manipulation using the powerful libraries NumPy and Pandas. The project aims to streamline the process of preparing and refining datasets for analysis and modeling purposes.

## Overview

The project involves the following key steps:

1. **Importing Data**: Utilizing NumPy and Pandas to import data files and read datasets efficiently.

2. **Handling Missing Values**: Identifying and replacing missing values with appropriate techniques, such as filling with `mean` values.

3. **Data Type Alignment**: Checking and adjusting data types to align with specific columns, along with column formatting using Pandas functions like `str` and `replace`.

4. **Outlier Detection**: Identifying outliers in various columns using the interquartile range method and establishing threshold criteria.

5. **Location Standardization**: Standardizing location data using the Pandas `replace` function.

6. **Establishments Exploration**: Handling `null` values in the Establishments column by replacing them with `median values`.

7. **Easy Apply Column**: Ensuring consistency in the Easy Apply column by standardizing inconsistent values.

8. **Rating Scale Consistency**: Establishing a consistent rating scale using `mapping` and the replace function.

9. **Salary Column Formatting**: Formatting the salary column into three separate columns for lower bound salary, upper bound salary, and average salary to enhance dataset readability.

10. **Data Validation**: Performing a final check on the data types and information of the transformed dataset to identify and rectify any minor discrepancies.

## Installation

To run the project, ensure you have Python installed along with the following dependencies:

- NumPy
- Pandas

You can install these dependencies using pip:

```
pip install numpy pandas
```

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
