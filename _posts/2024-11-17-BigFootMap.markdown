---
layout: post
title:  "Big Foot Sightings Interactive Map"
date:   2024-11-17 20:10:00 -0600
categories: jekyll update
---
<h2> Visual Map of Big Foot Sightings In the United States </h2>

{% include bigfoot_map.html %}

<p>In this visualization, I chose to use a map of the United States to represent each sighting of bigfoot, and plot them on each state in which they occured. I thought this would be an interesting way to visualize the data and for interactivity, have added the ability to see only the results of each individual state which I thought would be nice for people looking to see only one individual state. I used a few different encodings such as the Longitude, Latitude, and Colors. Mainly I did this to just plot each point in their respective state, as well as use different colors for different states, then what I did is use a tooltip that returned the county of which the account came from as well as the state and the date it was submitted. I thought it would be interesting to see where each took place to see occurances overtime. For this to be possible I did have to do some data cleaning, there were instances in where there was no longitude or latitude data available, so in order to make this map possible, I had to drop all of the NaN values in those two columns. Overall I think this all made for an interesting visualization of the data as well as some interactivity that allows for closer observation of the data as well as some filtering capabilities.</p>