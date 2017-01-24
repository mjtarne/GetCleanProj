#Codebook
## Data Cleaning

This data from the UCI HAR dataset was cleaned per the included file run_analysis.R. The 'training' and 'testing' datasets for 'x', 'y', and 'training' were merged, and then the mean and standard deviations were extracted from the 'features.txt' file. The headings were updated from the 'activity_labels.txt' file and the final data was written to 'average_data.txt'.

## Data Format

The 'average_data.txt' file includes a set of normalized (in the range [-1,1]) acceleration data for a number of activities and test subjects. The variables contain a number of x, y, and z accelerometer data collected via smartphone. The file "Codebook.txt" includes more details.