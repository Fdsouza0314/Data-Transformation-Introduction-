# Data-Transformation-Introduction-
Data Transformation in RStudio – NYC Flights 2013

This project explores how to transform and prepare data for analysis using RStudio and the dplyr package from the tidyverse. Working with the nycflights13 dataset — which contains information on over 336,000 flights that departed from New York City in 2013 — the project focuses on cleaning, organizing, and summarizing data to make it easier to understand and visualize.

It starts by taking a closer look at the structure of the dataset with simple R functions like View(), glimpse(), and summary(). From there, it walks through some of the most commonly used dplyr functions such as filter(), arrange(), mutate(), select(), rename(), and summarize(). Each function plays a specific role in manipulating data, and together they form a flexible toolkit for transforming datasets efficiently. The project also makes use of the pipe operator (|>), which allows multiple steps to be connected in a clear, logical sequence.

Through hands-on examples, the project demonstrates how to filter data based on specific conditions, sort records by time or value, create new calculated columns, and summarize grouped data to uncover trends — like average flight delays by month or destination. It also highlights the importance of using counts (n()) and understanding how grouping can affect summary statistics.

The final section includes a short case study using the Lahman baseball dataset, showing how data size and aggregation impact performance metrics. Overall, this project provides a practical look at how R can be used to turn raw data into meaningful insights — an essential skill for anyone working in data analysis or data science.

Reference: Wickham, H., & Grolemund, G. (2025). Data Transformation (Chapter 3) in R for Data Science (2nd ed.). Retrieved from https://r4ds.hadley.nz/data-transform
