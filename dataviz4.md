# Step one: find a data visualization  

## Plastic Pollution

Having stayed in multiple cities, I was exposed to different kinds of municipalities. Due to this, from some time I have been interested in learning about plastic usage, the effects of different ways its disposed and sustainable options for a lot of daily usage things.

This inspired me to look for data related to plastic pollution. I liked this data because it was showing the trend over time from 1980 and how plastic disposal has shifted. Since plastic has entered our life in every tiny thing we own, we forget about how its usage has changed over time.

This article talks about a lot of things including - 'how much plastic does the world produce?', 'How much plastic enters the world’s oceans?', 'How do we dispose of our plastic?' etc.

In this post, I will be critiquing the visualisation used under the heading:

### How do we dispose of our plastic?

#### The following chart talks about share of global plastic waste that is discarded, recycled or incinerated from 1980 through to 2015. How has global plastic waste disposal method changed over time?

<iframe src="https://ourworldindata.org/grapher/global-plastic-fate" loading="lazy" style="width: 100%; height: 600px; border: 0px none;"></iframe>

# Step two: critique the data visualization

# Step three: wireframe a solution

As per my critiquing, the chart they have used to show the change in plastic disposal methods over time is stacked area graph. It is able to show the ratio of how one category is increasing over other but it is not able to capture the values of each category in a particular year. It would also be confusing for a lot of audience who is not usually exposed to different kinds of data visualizations. 

Therefore, in my wireframe I have used group of column charts in which it can be clearly shown the value of each category every year. The group of column chart makes it easier to read every year indiviually as well. 

<img width="387" alt="image" src="https://user-images.githubusercontent.com/71149402/152909096-85e61809-930c-4911-8c14-26d308d54246.png">

# Step four: Test the solution

#### Primary Feedback:

In my primary feedback I was shared that the visualization is over all very readable and is easy to understand. Both my reviewers were able to share that the intended information was to understand the disposal methods of plastic globally over the years. They mentioned they were able to follow the trends for each of the categories. They did not find a lot of things confusing but had the following feedback:

- I should use consistent gap among the years shown for easier understanding.
- I should use an interval of 10 for the percentages instead of 20.
- The first reading has '0' value for Recycled and so the bar is missing and it makes it confusing.
- I was told 'green' was the apt color for 'Recycled' category, however 'Red' used for 'Incinerated' category was a little confusing.
- I should include titles for each axis.
- I could add a trend line to show how the bars are increasing and decreasing.
- I can also use stacked column charts.

They mentioned the intended audience would be able to easily read the visualization.

Based on the Primary feedback recieved I had created the grouped column charts in https://app.flourish.studio/projects.

I included majority feedback except the following :
- changing how I represent '0' value as I did not think there was another way to represent the data. 
- I did not use the stacked column chart as I realised it was giving the same effect as the original stacked area chart and it was difficult to find individual values.


#### Secondary Feedback:

The secondary feedback in class was not majorly around the visualizations, hence I could not make a lot of changes to the earlier version. Some of the points included were:
- The trend lines are not very helpful because the data was clear enough. It was rather making the visualization more crowded. I used this and changed back to just grouped column chart.
- If it was possible I should show the total quantities of the plastic waste disposal every year to give more context on the percentage share. I did not have this data from the orginal source and hence I could not include it. However it would have been an interesting exploration given the right dataset.

# Step five: Build your solution

After incorporating, all the feedback I have published the following visualizatrion:
<div class="flourish-embed flourish-chart" data-src="visualisation/8629165"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

