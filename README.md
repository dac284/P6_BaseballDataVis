# P6_BaseballDataVis
Udacity NanoDegree Project 6 - Creating a data visualization for a baseball dataset
<<<<<<< HEAD

### Summary

The project provides a data visualization of a small sample of baseball statistics.
I use a scatterplot to view the relation between batting average and home runs.
I also added animation/interaction to view some of the best players in more detail.

### Design

I chose a scatterplot because I wanted to see the relation between two quantitative 
variables. I originally used color to encode handedness as this is an unordered categorical variable, but later got rid of this encoding (see feedback section for more info).
I used transitions to zoom in on the best players and added mouseover interaction as an
easy way to view the names of some of the best players.

After getting feedback, I realized I definitely need a legend for handedness (again, I got rid of this later).
I chose not to add more data to the mouseover, because I did not have data that I thought would be informative (I only had height and weight and not anything about position, team, or year).
Need to be more clear about my message - the lack of a clear relation between BA and HRs. I highlighted this by explaining in the first panel that there appears to be a relation between BA and HRs overall, but when viewing players who have a significant amount of HRs (>50), that relationship mostly goes away. I tried to improve the clarity of the message by adding trendlines and r-squared values in my second iteration.


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

After my first submission, I realized the story I was trying to tell wasn't that clear. What I wanted to show was that from viewing all players, it made it look like as batting average went up, home runs went up. But when you only consider players over a certain 'threshold' (here taken somewhat arbitrarily to be 50 home runs and 0.200 batting average), then that trend almost entirely dissapears. There is still a small trend, but not much.

To better illustrate this in my revision, I included trendlines to show that trend before and after the transition more clearly, and I included the r-squared value as well. I also added a bit more context/description in the text, but I wanted to try to keep the text to a minimum. I also got rid of the handedness encoding, since that wasn't really showing anything different.


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
trendline
http://bl.ocks.org/biovisualize/1016860
arrays
https://github.com/mbostock/d3/wiki/Arrays

=======
>>>>>>> d054aa2bbea44c747aa09aa5ff33d188354a463e
