# Kickstarting with Excel

## Overview

### Louise's kickstarter for her play, *Fever* came close to her funding goal quickly
and she wants to learn more from a data analysis on plays and theater kickstarters.
The purpose here is to help her understand the patterns and trends of successful vs. 
failed kickstarters. Through this analysis we focused specifically on theater and plays 
outcomes based on funding goals and launch dates.

## Analysis and Challenges

### After filtering and sorting the data we can begin to visualize some trends. Chart, 
Theater_Outcomes_vs_Launch.png displays our results of kickstarters for plays for each
of the 12 months of the year. The blue, orange, and yellow lines represent trends
throughout the year for successful, failed, and canceled plays campaigns. It's clear
that campaigns launched in May and June have been more likely to succeed. We can also
see that November had the fewest failed campaigns.

### Let's look at chart, Outcomes_vs_Goals.png and we can look at different funding
goals vs. percentage of successful, failed, and canceled campaigns. Goals of $1,000
or less had a 76% success rate while goals above 45,000 were successful at a rate of
12% or less. There is an exception to the high success rate of smaller funding goals.
There is a 67% success rate for goals ranging from 35,000 to 45,000.

### There were a couple of challenges and difficulties that came up throughout this
analysis, most memorably when putting together the Outcome vs Goals line chart. In the
COUNTIF formulas used to break the data down by funding goals something wasn't right.
The chart was obviously not reflecting the data correctly. The first fix was to correct
the order of the function so that the funding range values were the first and last
of the function. It was still clear that something was off. I had forgotten to specify
that we only wanted to look at plays. After adding that column of data from our dataset
the outcomes changed but were still not correct. It ended up simply being that I was
using =< and => rather than <= and >=. A mistake that I resolved with a simple
google search. After all that work the formulas were fixed and the chart was accurately
displaying the results.

## Results

- We can conclude that May and June are the best months to launch a kickstarter for
plays and December is the worst with nearly half of the funding goals failed to be met.

- Smaller funding goals are more likely to be successfully achieved with the exception
of goals that fall between $35,000 and 45,000. Goals under $5,000 have the best chance
of success.

- There was not as much data for the high dollar goals so while the data says there's a
100% failure rate for campaigns with goals between 45 to 49,999 but there was only one
campaign in that range. Sets in the two ranges below that only had 3 and 6 total
campaigns so it was a very small sample.

- We could gather some more conclusions with graphs showing success rates based on the
number of backers and their average pledge. This would help with marketing decisions and
targeting demographics. We could also look for correlations between average donation
and the percentage funded for more insights.


