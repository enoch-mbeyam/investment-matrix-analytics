Statistical Matrix Calculator
Overview
A Python class for calculating various statistical metrics from a 3x3 matrix of investment returns.
Features

    Calculates mean, variance, standard deviation, max, min, and sum for each row, column, and overall
    Returns results in a dictionary for easy access
    Handles 3x3 matrices only

Usage

    Import the mean_var_std class
    Create a list of 9 numbers representing the investment returns (3 rows, 3 columns)
    Call the calculate method with the list as input

Example
input_list = [0, 1, 2, 3, 4, 5, 6, 7, 8]
output = mean_var_std.calculate(input_list)
print(output)

Output
A dictionary containing the calculated metrics, with the following structure:

    mean: [row_means, col_means, overall_mean]
    variance: [row_variances, col_variances, overall_variance]
    standard deviation: [row_stdevs, col_stdevs, overall_stdev]
    max: [row_maxes, col_maxes, overall_max]
    min: [row_mins, col_mins, overall_min]
    sum: [row_sums, col_sums, overall_sum]

Note

    The input list must contain exactly 9 numbers.
    The output is a dictionary with the metrics as keys and the calculated values as lists.

Contributing
  Contributions welcome! Please submit a pull request with your changes.
License
  MIT License
Author
[Enoch Mbeyam Awimba]
