# Americans' Automation Predictions

## Summary
This interactive visualization is for my final project in Udacity's "Make Effective Data Visualization" (project 6) course. In the visualization, I tackle the topic of automation in the workplace. The objective of the visualization is to effectively explore how the average American perceives the threat of automation in their workplace and in general. The input data comes from a pew research questionnaire.

## Design


  **Bar graph**: I use bar graphs as a way to compare categorical data

  **Size**: I use size to make relative comparison amongst cohorts (conservative vs. moderate, etc.)

  **Percentages**: Percentages are used(y-axis) to make comparisons between cohorts ("definitely will" vs. "definitely won't")

  **Tooltip**: Gives more details about a certain bar

  -- Updated (15 Apr 2017) --

  **Color hue**: The main bars use a slightly darker color to attract your attention before the children graphs transform

  **Pre-attentive Processing**: Red highlighting is used to both beckon the user to click and also
  to remind them what category they're exploring.

  **Animated Transitions**: Cool to look at

  **Relative Comparisons**: I changed the data wrangling so the bars on the right represent the percentage of that cohort
  that gave that particular answer (e.g. 18% of all males with a job were "not too concerned" about being replaced with someone cheaper).


## Installation
  Click link to view:
  http://bl.ocks.org/culight/raw/1cb11a7a7909aed28a84036533c61b91/

## Feedback
  Here's some feedback that I've received:

  - Two girls in coffee shop
      >  - First thing I noticed were the graphs on the right
      >  - I wonder how many people were surveyed and where the info came from
      >  - Not as many people were concerned about job security as I expected
      >  - Compartmentalization of information was useful
      >  - I didn't know to click on the bar

  - My brother
      >  - The first thing I noticed was the title and question above and then the bar graph
      >  - Who conducted survey, sample size, margin of error, when it was conducted
      >  - Opinions between different groups were more equal than I expected
      >  - People do feel like robots will take over jobs… just not their jobs
      >  - Clicking on the bar was not obvious. Side part should already be populated.

  - mmlak_0109
      >Good work so far. In general, the information is presented in a clear manner, and the animations are simple and aid in understanding. >Here the main things for me that come to mind in terms of problem areas:
      >
      >1) It's a bit hard to determine the exact percentage of the responses in the main bar graph since there is no tool-tip or dash-line >pointing out exactly where the percentage falls. You have this function in the small multiple bar graphs, but not the main one. I would >add this function back into the main bar graph.
      >
      >2) On some the small multiple graphs the variable names on the x-axis are completely vertical. This makes reading the variable names a >little hard. I would suggest setting them at at least 45 degrees to make them more easily readable. I've adapted this code to do it in >my own visualization:
      >http://stackoverflow.com/questions/17791926/how-to-rotate-x-axis-text-in-dimple-js
      >
      >3) The percentages in the small multiples are a little confusing. For example, in the first graph for the question "How concerned are you >that your employer will find someone who is willing to do your job for less money?" If I click on the response category "Not At All >Concerned" and then look at the breakdown by sex in the small multiple graph, it gives 67% for females and 62% for males. Do these >percentages represent the percent of the total respondents, or just the percent of the specific response category? I'm assuming the >former, but it isn't completely clear.

## Resources
  * d3js: https://d3js.org/ (version 4.0)
  * JQuery: https://jquery.com/
  * dimple.js: http://dimplejs.org/
  * Data Source: http://www.pewinternet.org/2016/03/10/public-predictions-for-the-future-of-workforce-automation/
  * Mike Bostock's "Let's Make a Bar Chart": https://bost.ocks.org/mike/bar/

## Future Work
  * Make the content more responsive
  * Optimize the data aggregation algorithm
  * Try to delve deeper into the data on the right side

## Credits
Demerrick Moton (dmoton3@gatech.edu)
