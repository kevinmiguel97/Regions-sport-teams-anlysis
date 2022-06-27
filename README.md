<p align="center">
  <img width="700" src="https://www.reddit.com/r/MapPorn/comments/9hgfk8/us_counties_by_closest_big_four_sports_team/">
</p>

# Regions-sport-teams-anlysis

## Description
Follow the analysis in [Notebook](Regions_analysis.ipynb)

In this assignment we will read a file of metropolitan regions and associated sports teams from [assets/wikipedia_data.html](assets/wikipedia_data.html) and answer some questions about each metropolitan region. Each of these regions may have one or more teams from the "Big 4":
- NFL (football, in [assets/nfl.csv](assets/nfl.csv))
- MLB (baseball, in [assets/mlb.csv](assets/mlb.csv)) 
- NBA (basketball, in [assets/nba.csv](assets/nba.csv)
- NHL (hockey, in [assets/nhl.csv](assets/nhl.csv)). 

It is important to keep in mind that all the analysis made is from the perspective of the metropolitan region, and that this file is the "source of authority" for the location of a given sports team. Thus teams which are commonly known by a different area (e.g. "Oakland Raiders") need to be mapped into the metropolitan region given (e.g. San Francisco Bay Area). This will require some human data understanding outside of the data we've been given

For each sport we are going to answer the question: **what is the win/loss ratio's correlation with the population of the city it is in?** 
(Win/Loss ratio refers to the number of wins over the number of wins plus the number of losses)

