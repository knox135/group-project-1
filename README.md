# group-project-1

# Group Project 1 - 2023/24 NBA Season and Playoff Analysis

In this challenge we looking into past and current seasonal data to project the possible outcome of the playoffs. The data will be gathered from rapid api which is an overlay to api-sports. With a focus on the final 8 teams playing.
Oklahoma City Thunder vs. Dallas Mavericks, Minnesota Timberwolves vs. Denver Nuggets, Boston Celtics vs. Cleveland Cavaliers, Indiana Pacers vs. New York Knicks'

## Workflow

- Gather various datapoints and output the dataframes to CSV for a snapshot to work from
    1. Seasonal (2015-2024)
    2. Teams Statistics (2015-2024)
    4. Player Statistics (2015-2024)
- Combined necessary data points
    1. Seasonal game data with Player game data into a single DataFrame
- Assess the data
    1. Looking at the +/- values assigned per game per player to forecast the overall team matchups to determine the potential winner
- Use Prophet to forecast future data
    1. Apply the DataFrame(s) to Prophet using 'fit'
    2. Visualize the data to see the forecasted results

## Usage

The notebooks to review and run can be found in the matchups folder.
1. cavsvceltics.ipynb
2. knicksvpacers.ipynb
3. mavsvthunder.ipynb
4. nuggetsvwolves.ipynb

These notebooks are the analysis of player and team data for the each matchup of the second round of the 2024 NBA Playoffs. All of the remaining notebooks found within team players, teams folders and the root folder were utilized for data gathering to provide a snapshot of data in time that we could collectively use for the examination and forecasting to determine the winners of the matchups.

The supporting notebooks demonstrate data lookup from an api, loading it into a dataframe and outputting that data as a csv file.

## Summary

Overall we have forecasted the Boston Celtics, New York Knicks, Minnesota Timberwolves and Oklahoma City Thunder going to the their Conference Finals. The forecasting of our model for the series matchups has successfully predicted the outcome of the Boston-Cleveland matchup with Boston defeating Cleveland. The other series are still in progress and accuracy yet to be determined.


## Resources

1. https://rapidapi.com/api-sports/api/api-nba
