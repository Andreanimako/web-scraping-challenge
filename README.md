# web-scraping-challenge

Module 11 Challenge

This new assignment is a web scraping challenge that requires 2 deliverables:

Deliverable 1: To scrape titles and preview text from Mars news articles.

Deliverable 2: To scrape and analyze Mars weather data, which exists in a table.


Deliverable 1:

Involved scraping data from a Mars news website using automated browsing with Splinter to visit the Mars news site, and extracting the html code with Beautiful Soup. The titles and preview text of the news articles were scraped, extracted and stored into a list of dictionaries.

This was done in a jupyter notbeook named "part_1_mars_news" and stored in this repository as "part_1_mars_news.ipynb".

The Titles of the news artice and their preview text are shown below:

title: "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm",
  preview: 'For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27.'
  
title: "NASA Prepares to Say 'Farewell' to InSight Spacecraft",
  preview: 'A closer look at what goes into wrapping up the mission as the spacecraft’s power supply continues to dwindle.'
  
 title: 'NASA and ESA Agree on Next Steps to Return Mars Samples to Earth',
  preview: 'The agency’s Perseverance rover will establish the first sample depot on Mars.'
  
 title: "NASA's InSight Lander Detects Stunning Meteoroid Impact on Mars",
  preview: 'The agency’s lander felt the ground shake during the impact while cameras aboard the Mars Reconnaissance Orbiter spotted the yawning new crater from space.'
  
 title: 'NASA To Host Briefing on InSight, Mars Reconnaissance Orbiter Findings',
  preview: 'Scientists from two Mars missions will discuss how they combined images and data for a major finding on the Red Planet.'
  
 title': 'Why NASA Is Trying To Crash Land on Mars',
  preview: 'Like a car’s crumple zone, the experimental SHIELD lander is designed to absorb a hard impact.'
  
 title: 'Curiosity Mars Rover Reaches Long-Awaited Salty Region',
  preview: 'After years of climbing, the Mars rover has arrived at a special region believed to have formed as Mars’ climate was drying.'
  
 title: 'Mars Mission Shields Up for Tests',
  preview: 'Protecting Mars Sample Return spacecraft from micrometeorites requires high-caliber work.'
  
 title: "NASA's InSight Waits Out Dust Storm",
  'preview': 'InSight’s team is taking steps to help the solar-powered lander continue operating for as long as possible.'
  
 title: "NASA's InSight 'Hears' Its First Meteoroid Impacts on Mars",
  preview: 'The Mars lander’s seismometer has picked up vibrations from four separate impacts in the past two years.'
  
 title: "NASA's Perseverance Rover Investigates Geologically Rich Mars Terrain",
  preview: 'The latest findings provide greater detail on a region of the Red Planet that has a watery past and is yielding promising samples for the NASA-ESA Mars Sample Return campaign.'
  
 title: 'NASA to Host Briefing on Perseverance Mars Rover Mission Operations',
  preview: 'Members of the mission will discuss the rover’s activities as it gathers samples in an ancient river delta.'
  
 title: "NASA's Perseverance Makes New Discoveries in Mars' Jezero Crater",
  preview: 'The rover found that Jezero Crater’s floor is made up of volcanic rocks that have interacted with water.'
  
 title: "10 Years Since Landing, NASA's Curiosity Mars Rover Still Has Drive",
  preview: 'Despite signs of wear, the intrepid spacecraft is about to start an exciting new chapter of its mission as it climbs a Martian mountain.'
  
 title: "SAM's Top 5 Discoveries Aboard NASA's Curiosity Rover at Mars",
  preview: '“Selfie” of the Curiosity rover with inset showing the SAM instrument prior to installation on the rover."




Deliverable 2: 

Involved scraping and analyzing Mars Weather Data.
The Mars Weather data website was opened using Splinter and the HTML table was extracted using Beautiful soup and  saved into a Pandas DataFrame named "df". The columns were appropriately named and the data types appropriately changed to allow easy analysis.

The data was analyzed usind pandas to answer and visualize the following questions: 

1.How many months exist on Mars?

12

2.How many Martian days' worth of data are there?

1867

3.Which month, on average, has the lowest and highest temperature ?

lowest - month 3

highest - month 8

4.Which month, on average, has the lowest  and highest atmospheric pressure?

lowest - month 6

highest - month 9

5.How many terrestrial days exist in a Martian year?

A year on Mars appears to be about 675 days.



This analysis was done in a jupyter notbeook named "part_2_mars_weather" and stored in this repository as "part_2_mars_weather.ipynb".

The dataframe "df" was then saved into a csv file into the "output" folder within this repository's main branch as "mars_weather.csv".
