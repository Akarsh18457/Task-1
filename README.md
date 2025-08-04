I have completed the data cleaning task on netflix_titles.csv dataset. Here is a summary of the changes made:

Missing Values:

Missing values in the director, cast, and country columns were filled with 'Unknown'.
Missing values in the date_added column were filled using the ffill (forward-fill) method.
Missing values in the rating column were filled with 'Unknown'.

Inconsistent Formatting and Data Types:

The date_added column, which was initially in string format, was converted to a proper datetime data type.
The duration column was split into two new columns, duration_in_min for movies and duration_in_seasons for TV shows, to handle the inconsistent units.
I identified and corrected three rows where the rating column contained duration values (74 min, 84 min, 66 min) and replaced them with 'Not Rated'.
The cleaned dataset is available in the file netflix_titles_cleaned_dataset.csv.

Blank values were also addressed during the cleaning process.
