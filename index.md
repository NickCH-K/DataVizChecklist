# Data Visualization Checklist

## Develop

* Read the documentation for your data
* Read the description of the variables you might use - what they are and what scale they're measured in
* Figure out an interesting insight that you can convey with your data (the "story")
    - Is it accurate? Does the data actually support that insight?
    - Is it actionable, deeply interesting, or does it help you understand how the world works? Ask "if I learned this insight, would I care?" If the answer is no, try something else. (Tip: "Group X has the highest average value of variable Y" is a snooze of a story for most X and Y. If you're going to do that one, you're gonna have to work to convince the reader to care)

## Design

* In order to understand your insight, figure out what kinds of *continuity* should the reader see (for "the poverty rate has fallen over time" you should be able to see continuous changes in time), and what kinds of *contrast* they should see (for "the poverty rate has fallen more in country X than country Y" you need it to be easy to contrast changes in X against changes in Y)
*  Determine what aesthetics you will use (x, y, color, line type, size, etc.) with each relevant variable. Make sure they are appropriate for making the continuity/contrasts you want
* Determine the geometry (line, bar, point, area, lollipop, etc.) that will best get your story across
    - Specific tips: line graphs require an X axis with a natural order. Scatter plots are hard to read with too many points, and need continuous X and Y axes. Most geometries have a hard time graphing lots and lots of separate categories.
* Draw a quick sketch by hand and make sure you like it

## Detail

* Make an initial rough graph
* Select aesthetic elements - color, shapes, etc. - that are easy to read and are colorblind-friendly. Make sure the font size is large enough to read.
* Label axes, legends, and values using common-language terms, not the variable name in your statistics package (and definitely get rid of any scientific notation)
* Make sure the font size is big enough to read!
* Move information where it's easy to see - labels should go near the data. Legends can often be absorbed into the graph, and so on.
* Add titles, highlighting, and annotation that helps draw the reader's focus to your story
* Remove clutter unrelated to your story
* Ask yourself or a friend "if I didn't know the story I was trying to tell, would I naturally figure it out by looking at the graph?" and if not, make it more clear. 
