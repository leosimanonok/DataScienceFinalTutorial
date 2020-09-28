layout: page
title: "Milestone1"
permalink: /Milestone1/

  Throughout the past decade, data science has emerged as a leading field of study and industry. Data analysis has become critical in tackling societal problems and 
tracking certain trends in order to arrive at informed, logical solutions. For our final project, we have decided to study New Orleans income and property data 
to identify the prevalence of gentrification in different neighborhoods. As Tulane students, it is easy to become trapped in the uptown bubble and forget about the 
impact we have on the rest of the city’s people, economy, and culture. It is no secret that New Orleans as a whole is a victim of gentrification. Part of what makes 
the city so unique is its rich history and resilience, something to which none of the 13,000 people from out of state who have moved here from 2012-2016 can bear 
witness. That being said, our goal for this project is to find meaningful insights in our datasets which we can offer to our partners, hopefully inspiring positive 
changes in New Orleans.
  Initially, one of the datasets we hoped to get our hands on was property value data. Looking at housing prices would allow us take a holistic look at gentrification
and possibly track the movement of affluent people to previously poorer neighborhoods. Unfortunately, property value data is notoriously hard to collect in New 
Orleans. Because of this, we decided to focus instead on poverty rates and income data. To this end, we found census data from the years 2010-2018 which estimates 
the median income and poverty rate of every county in the USA.
Another dataset we are looking at describes the racial profile of different neighborhoods in and around New Orleans. We hope to use this data in conjunction with 
the previously discussed census data in order to show how gentrification changes the make-up of neighborhoods. Ideally, we would like to show where the displaced 
citizens moved after their neighborhoods were gentrified. 
  The dataset we decided to load into our notebook for this milestone contains the median income and poverty rate for each parish in Louisiana. Loading this dataset 
came with a host of struggles. The biggest struggle was figuring out which character(s) to use as a delineator. Some of the columns in the data set were separated by a 
single space, some by tabs, and some by longer segments of white space. In addition, one field in particular, the name of the county, had white space in the middle of 
the value, e.g. Orleans Parish. In order to be able to load the data correctly, we decided to use r"\s+" as our delineator, which specifies any kind of white space. 
This meant that the names of the counties had to have their spaces removed by hand.
  In terms of our meeting plan, we have set weekly meetings on Mondays at 1pm to analyze our progress and plan for any upcoming due dates or milestones. Depending on 
our availability and wellbeing, we have decided to meet in person in the library to avoid technological complications. In the event that we need to meet virtually,
we will maintain these meeting times via Zoom. For any code we are writing for the final project, we will do so in our private GitHub repo attached to our final 
project page. We have already established that each of us are able to connect, pull, and push to it from our local machines.
