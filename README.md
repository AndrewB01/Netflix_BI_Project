# Netflix BI Project

question to solve:
- Provide information/Analysis around ratings and numbers of votes behind them and sharing how is this distributed across countries, genres and title

## Data preparation process
1) load file (CSV format)
2) remove columns not needed to this project
  - Popular_rank
  - certificate
  - endYear
  - episodes
  - language
  - summary
  - isAdult
  - cast
3) Rename Columns to a more user friendly and understanable names and format
4) Review and adjust data type
5) Data clensing
  - Replace error or in runtime for null
  - filter type to remove
      - blanks
      - shorts
      - video
      - videoGame
    - filter Rating to remove
        - blanks
    - filter Country to remove
        - blanks
## Data Modeling
