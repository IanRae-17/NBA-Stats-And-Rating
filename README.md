# NBA-Stats-And-Rating
This project pulls a NBA seasons total and advanced statistics and then calculates skill ratings for the players. Data is pulled from Basketball Reference (https://www.basketball-reference.com/). Output data is in csv format for all years as well as individual years.

# Config
The config file allows for editing:

  The range of seasons data is pulled for:
  startingYear - First season data is pulled for
  finalYear - Last season data is pulled for
  
  The weight each statistic has in rating calculations:
    Offensive:
      orbWeight     - Offensive Rebounds
      astWeight     - Assists Per Game
      ppgWeight     - Points Per Game
      astpcWeight   - Assist Percentage
      owsWeight     - Offensive Win Share
      tspcWeight    - True Shooting Percentage
      perWeight     - Player Efficiency Rating
      obpmWeight    - Offensive Box Plus Minus
      ptsWeight     - Total Points
      usgpcWeight   - Usage Percentage
    Defensive:
      drbWeight     - Defensive Rebounds
      stlWeight     - Steals Per Game
      blkWeight     - Blocks Per Game
      stlpcWeight   - Steal Percentage
      blkpcWight    - Block Percentage
      dwsWeight     - Defensive Win Shares
      dbpmWeight    - Defensive Box Plus Minus
      
  Ratings Range:
    MAX_RATING - Rating of the best player
    MIN_RATING - Rating of the worst player
