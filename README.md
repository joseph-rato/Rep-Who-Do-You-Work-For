# Rep-Who-Do-You-Work-For


## Background and Overview

Overview for this project is the ability to search an area code and learn who your representatives are. Then to be able to open up the politician and learn information on their past voting history, who they've been accepting donations from and what public opinion of them is based on locational data of twitter.  

I personally think that there are a lot of resources out there that can give us a better understanding of our political system. However this is what I like to call percieved trancparency. It's precieved trancparency because the data is there but in so many disconnected areas that it's hard to have a whole understanding of what the overall situation is. To get an overall understanding of who I'm voting for and how they're doing representing my interests, I need to find data and make it readable. This hasn't been done well and I want to attempt my spin on it. 


## Functionality and MVPs

### Functionality

Search zip code and return a list of politicians in that area code that represent you. 

Clicking on representative returns a few charts that show:
* Campaign funding from biggest donations down
* Aggregation of votes along party lines
* twitter opinion synthesizer based on location and politician's name (maybe political party as well) 

### MVPs

- [] api pull based on location to get politicians 
- [] api pull of data based on politician name 
- [] graphs to show data for campaign fund, aggregation of votes along party lines
- [] 

brieft summary 
I want to be able to search a zip code then return a list of politicians 
then i want to select a politician and get informational charts that show:
* info on how a politician voted, 
* whos a politician been accepting donations from 
* and what public opinion is on donation of money



The technologies I want to use: 
* some type of opinion synthesiszer and location selection for twitter opinions
* d3 for data visualization

The data I want to use
* open secrets api for campaign funding information
* govtrack for voting data 
* twitter scraper or twitter api for locational information and tweets for the synthesizer

future things have a cool google api that outlines the district of politician is in control of
maybe have a color graph of the area and how its seperated by type of voter