HW02: Netflix Titles Data Preprocessing

This Python script processes a TSV file (netflix_titles.tsv) of Netflix movies, extracts relevant details, and saves the cleaned data as a JSON file (hw02_output.json). The script focuses on essential columns like title, directors, cast, genres, and release decade.

Functionality
Data Extraction: Reads only relevant columns (title, director, cast, genres, release year).
Transformations:
List Conversion: Converts comma-separated strings (directors, cast, genres) into lists.
Decade Calculation: Rounds each movie’s release year to its decade (e.g., 1997 → 1990).
Output: Saves cleaned data in JSON format for easy further analysis.
