---
layout: post
title:      "Theme Park Attractions Around the World"
date:       2019-02-11 02:14:06 +0000
permalink:  theme_park_attractions_around_the_world
---


When given our first assignment to create a CLI that would scrape information from an external website, I had several ideas in mind that were of interest to me. One that stood out more than any that I thought would make a great gem is theme park attractions.

I have always been a huge fan of theme parks, probably since the first time I visited Disney World when I was 7 years old. I love any type of ride, from roller coasters, to dark rides, slow rides, water rides, and anything in between. I'm always on the look out for some good theme parks to go to.

The gem that I built scrapes its data from ThemeParkTourist.com and it pulls the top 100 theme park attractions in the world sorted by their rating. It is rather simple as it just loads the 100 attractions by pulling 15 at a time based on the number entered in by the user, plus the park they are located in from the main index page with the attractions listed on it. It uses nokogiri and open-uri to pull the information and you can get more information on each ride by typing in the index number of the ride after viewing the list.

The attributes I used for the extra information you can pull are located on the individual attractions page on the ThemeParkTourist website, they are: 

1. Ride Type
2. Park URL
3. Opening date of the attractions
4. Brief Description of the ride

The most challenging part of this project was trying to find out how to pull the information for the ride type (and only the ride type) due to it being in one of a few <p> tags that were all located in the same <div> tag with no classes or IDs to tell them apart.

Overall I enjoyed working on this project and finally getting everything to work and communicate correctly together.
