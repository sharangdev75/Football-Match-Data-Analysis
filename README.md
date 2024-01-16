# Football-Match-Data-Analysis
This project focuses on analyzing a comprehensive dataset containing results from international men's soccer matches dating back to 1872. The dataset exclusively includes matches involving national teams affiliated with continental confederations



Dataset Details
all_matches.csv
This dataset consists of 48,964 entries and includes the following columns:

date: Date of the match (when the date is unknown, 31/12 is used by default, or the last day of the month if known).
home_team: Name of the home team.
away_team: Name of the away team.
home_score: Full-time home team score, including extra time (excluding penalty shootouts).
away_score: Full-time away team score, including extra time (excluding penalty shootouts).
tournament: Name of the tournament.
country: Name of the country where the match was played.
neutral: Boolean column indicating whether the match was played at a neutral venue (TRUE/FALSE).
countries_names.csv
This supplementary dataset provides additional information about country names used in the main dataset:

original_name: Country name used in the main dataset.
current_name: Current country name or the name of the country that inherited the historical data.
The national team names in the main dataset are those used at the time of the match. The countries_names.csv file can be utilized to match current team names.



Usage
Researchers, analysts, and soccer enthusiasts can leverage this dataset to perform various analyses, including team performance trends over time, tournament-specific insights, and the impact of neutral venues on match outcomes. The countries_names.csv file facilitates mapping historical country names to their current counterparts for a more comprehensive understanding.
