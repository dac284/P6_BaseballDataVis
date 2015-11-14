# P6_BaseballDataVis
Udacity NanoDegree Project 6 - Creating a data visualization for a baseball dataset
<<<<<<< HEAD

### Summary

The project provides a data visualization of a small sample of baseball statistics.
I use a scatterplot to view the relation between batting average and home runs.
I also add color to explore the handedness of the players and added animation/interaction
to view some of the best players in more detail.

### Design

I chose a scatterplot because I wanted to see the relation between two quantitative 
variables. I used color to encode handedness as this is an unordered categorical variable.
I used transitions to zoom in on the best players and added mouseover interaction as an
easy way to view the names of some of the best players.

After getting feedback, I realized I definitely need a legend for handedness.
I chose not to add more data to the mouseover, because I did not have data that I thought would be informative (I only had height and weight and not anything about position, team, or year).
Need to be more clear about my message - the lack of a clear relation between BA and HRs. I highlighted this by explaining in the first panel that there appears to be a relation between BA and HRs overall, but when viewing players who have a significant amount of HRs (>100), that relationship goes away (This is interesting because it suggests power hitters are not necessarily getting more hits, just more big hits).


### Feedback

I posted a url to my data vis on udacity's discussion forums here:
https://discussions.udacity.com/t/feedback-for-data-vis/37326/3

I also showed my data visualization to friends and family in person to get their feedback.

I got the following feedback (summarized from multiple viewers):
- some viewers noticed outliers with high HRs and low BAs
- Add a legend for the handedness to increase clarity
- not much relation between BA and HR in general
- focusing on the high performers was nice
- more info about each player would be nice (position, year, team)
- many performers are around average but some are much better
- what am i showing but coloring by handedness?
- more text on the second panel for context


### Resources

css help
http://css3buttongenerator.com/
http://www.w3schools.com/css/css_rwd_images.asp 
legend help
http://stackoverflow.com/questions/13573771/adding-a-chart-legend-in-d3
transitions
https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_ease
mouseover/tooltip
http://bl.ocks.org/biovisualize/1016860

=======
>>>>>>> d054aa2bbea44c747aa09aa5ff33d188354a463e
