# pitch-classification-analysis
This repository contains all the code for my MLB pitch classification analysis that I posted on [Medium](https://towardsdatascience.com/measuring-how-well-pitchers-hide-their-pitches-f61f076d91f4?source=friends_link&sk=be1b11123ccefe7174183e8cc67bf649)

## Analysis Summary
The problem that this analysis tackles is how some MLB pitchers give away what pitches they throw by their varying release points.
In my analysis I attempt to quantify how well a certain pitcher can hide what pitch they throw by using a Gradient Boosted Model to try and classify their pitch
type based on their release point and the count in which the pitch was thrown. The better the model performs, the worse the pitcher is at hiding his pitches.
## Data Source
Data was gathered by using the pybaseball library which scrapes pitch-by-pitch data from Fangraphs and Baseball Savant
## Applications
I believe that this model could be very useful for MLB teams for both hitters and pitchers. For hitters it can be used to identify pitchers that have distinct
differences in release point. Hitters can the review tape and study their release points to better identify what pitch that pitcher will throw. 
For pitchers, it can be used as a warning flag to tell them that they need to try and replicate their release points better. 
