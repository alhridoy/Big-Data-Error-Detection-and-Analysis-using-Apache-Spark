# Big-Data-Error-Detection-and-Analysis-using-Apache-Spark

Developed a robust PySpark pipeline for data loading, preprocessing, and error detection, ensuring high-quality data.

Loaded the 'tax_dirty.csv' dataset into a Spark DataFrame using PySpark, enabling distributed data processing.
Performed comprehensive data preprocessing, including handling missing values and inferring the schema, ensuring data integrity.
Implemented advanced error detection mechanisms using PySpark functions and regular expressions to identify data inconsistencies and anomalies.
Applied customized error detection rules to specific columns ('f_name', 'city', 'zip', 'rate', 'state_city', and 'marital_child'), ensuring accurate error identification.
Engineered additional columns with binary indicators to flag the presence of errors, facilitating error analysis and further data quality improvement.
Conducted thorough error analysis, quantifying and reporting the number of errors in each column ('f_name_error', 'city_error', 'zip_error', 'rate_error', 'state_city_error', and 'marital_child_error').
Achieved outstanding performance in error detection with a logistic regression model, attaining a remarkable accuracy of 90.8%.
Demonstrated the impact of the pipeline by successfully applying it to new datasets, proactively identifying and resolving data quality issues, leading to improved decision-making and optimized processes.
