# Rep-Who-Do-You-Work-For


## Background and Overview

Overview for this project is to show how a politician votes according to the twitter oppinion and campaign funding. Maybe also along party lines.

## Functionality and MVPs

### Functionality

want to search a politician and return:
graph that has funding 
graph against that has twitter opinions 
graph that shows votes on key subjects

### MVPs

- [] graph that shows past votes on key subjects
- [] graph that shows past twitter synthesiser on key subjects per location
- [] pie graph that shows top funders for campaign funding

## Archiitecture and Technologies

### sentiment node.js
    - https://github.com/thisandagain/sentiment
    - takes the setiment of a string by measuring the usage of positive or negative words in relation to a subject
### D3
    - usage of graphs and animation to properly show results

## Implementation Timeline

day 1
    learn how to use d3
day 2
    try to implement basic pulls for data
day 3 
    represent data in graphs
day 4 
    put animations
day 5
    stylize
day 6
    stylize

## Wireframe
![Alt text](wireframemainpage.png?raw=true "Wireframe")

## Data Sources 

- govtrack.us api
    - vote information on politician
    - politician by zip
- opensecrets.org api
    - campaign financing by politician
- twitter.com api
    - public opinion data
