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

The primary notebook to review is that of nuggetsvwolves.ipynb. This notebook is the analysis of player and team data for the Denver Nuggets and the Minnesota Timberwolves. All of the remaining notebooks found within the root folder of the project as well as those in the team players and teams folders were utilized for data gathering to provide a snapshot of data in time that we could collectively use for the examination and forecasting to determine the winner of the matchup.

The supporting notebooks demonstrate data lookup from an api, loading it into a dataframe and outputting that data as a csv file.

## Summary

Overall we have forecasted the Boston Celtics, New York Knicks, Minnesota Timberwolves and Oklahoma City Thunder going to the their Conference Finals. The forecasting of our model for the series matchups has successfully predicted the outcome of the Boston-Cleveland matchup with Boston defeating Cleveland. The other series are still in progress and accuracy yet to be determined.


## Resources

1. https://rapidapi.com/api-sports/api/api-nba