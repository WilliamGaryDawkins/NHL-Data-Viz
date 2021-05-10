# NHL-Data-Viz
NHL data visualizations

This project works to create interactive visualizations using ipywidgets in a jupyter notebook that allows the user to explore a relational database containing data from NHL seasons over multiple years. Pyspark SQL was used in queries to extract data for the visualizations as it is the hope that this type of work could be extended to databases large enough to require distributed storage. The work contains five visualizations:

1. The user is asked for a given year, stat and number of players to display. A bar plot is then produced displaying the top ranked given number of players ordered by the given stat. The stat totals and player names are presented.

2. 
