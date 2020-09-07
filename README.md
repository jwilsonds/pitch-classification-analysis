# pitch-classification-analysis
This repository contains all the code for my MLB pitch classification analysis that I posted on [Medium](https://towardsdatascience.com/measuring-how-well-pitchers-hide-their-pitches-f61f076d91f4?source=friends_link&sk=be1b11123ccefe7174183e8cc67bf649)

## Analysis Summary
The problem that this analysis tackles is how some MLB pitchers give away what pitches they throw by their varying release points.
In my analysis I attempt to quantify how well a certain pitcher can hide what pitch they throw by using a Gradient Boosted Model to try and classify their pitch
type based on their release point and the count in which the pitch was thrown. The better the model performs, the worse the pitcher is at hiding his pitches.
## Data Source
Data was gathered by using the pybaseball library which scrapes pitch-by-pitch data from Fangraphs and Baseball Savant
## Applications

