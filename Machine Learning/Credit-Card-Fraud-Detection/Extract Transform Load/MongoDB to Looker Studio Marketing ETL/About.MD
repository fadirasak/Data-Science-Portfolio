Instructions
To use the script, make sure you have Python and the required libraries installed.
Fill in the necessary information in the script, such as the MongoDB connection URL, collection names, and BigQuery destination table.
Execute the script to connect to the MongoDB database, extract the data, and export it to BigQuery.
The script performs category aggregation for the last three months and filters the data based on the 'created' date field.
The extracted data is converted into a pandas DataFrame and casted to specific data types for efficient memory usage before exporting to BigQuery.
Note: Before executing the script, please make sure to understand what it does and verify the configurations.