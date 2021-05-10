# NHL-Data-Viz
NHL data visualizations

This project works to create interactive visualizations using ipywidgets in a jupyter notebook that allows the user to explore a relational database containing data from NHL seasons over multiple years. Pyspark SQL was used in queries to extract data for the visualizations as it is the hope that this type of work could be extended to databases large enough to require distributed storage. The work contains five visualizations:

1. The user is asked for a given year, stat and number of players to display. A bar plot is then produced displaying the top ranked given number of players ordered by the given stat. The stat totals and player names are presented.

2. A visualization of the final standings for a given NHL season. The user gives a season year they are interested in and a plot is shown of all NHL teams ranked by points earned in that season.

3. A world map displaying the distribution of NHL players' nationalities. The user gives the season they are interested in and can specify if they are interested in goalies or regular players, a world map is then shown with nations coloured by number of players for that season.

4. Scatter plots/Heat maps of a player's shots and goals for a given season. The user enters a player they are interested in, the season and whether they want to see shots or goals. The visualization then produces a scatter plot or heat map according to the user's choice displaynig where the given player took their shots or scored their goals from on the ice surface.

5. Scatter plots for events in a given game. The user gives a game they are interested in viewing and the event they are interested in (shots, goals, hits, takeaways etc.) and a scatter plot shows where on the ice these events took place during the game, coloured by each team. 
