# Investigate a Dataset
## by Opeyemi Rafiat Fasasi


## Dataset

The TMDB movie dataset contains information like budget, revenue, cast, title, director, genres, votes etc. of the movies listed on TMDB.
The dataset can be found here: https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd1c4c_tmdb-movies/tmdb-movies.csv&sa=D&ust=1532469042115000


Here are some of the steps taken during investigation: 
- Used .head(), .shape and .info() to understand the structure of the data
- Checked for duplicates using .duplicated() and summary statistics using .describe()
- Renamed the columns of some variables using .rename()
- Changed the datatypes of some variables using .astype() and to_datetime()
- Selected the columns needed for the analysis.
- Visualized the distribution of adjusted budget and revenue using bar chart
- Showed the yearly trend of movies count. 
