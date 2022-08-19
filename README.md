# An Exploratory Analysis of Singapore's Public Bus Data 

## Prelude 

![bus image](https://github.com/aanghs22/gitnetwork/blob/main/Images/bus%20image.jpeg?raw=true)
<br> _Image credits: Land Transport Guru_
<br> As a frequent user of the public transportation system in Singapore (especially the buses), I always find myself wondering about the transportation system - is the load of commuters _always_ this heavy for all bus services? Where do people like to go via the public bus? Is there a neighbourhood that relies greatly on the buses to arrive at their destination? 

## Project Objectives 
In this project, I explore the publicly available datasets on buses with the intention of: 
<br> (1) gaining a better understanding of how people utilise the public buses to move from place to place, 
<br> (2) identifying dead zones in Singapore (areas least accessible by bus), and 
<br> (3) simply exploring the dataset. 

## Resources needed for this exploration
The datasets used include: 

<br> (1) Master Plan 2019 Planning Area
	<br> * Segments the land area of Singapore into 3 different levels - Region, Planning Area and Subzone
<br> (2) Bus Stops Dataset [LTA Datamall](https://datamall.lta.gov.sg/content/datamall/en.html)
    <br> * Provides the bus stop code and geo-coordinates for every bus stop in Singapore 
<br> (3) Origin-Destination Passenger Volume Trip Records [LTA Datamall](https://datamall.lta.gov.sg/content/datamall/en.html)
    <br> * Sums the total trips from one bus stop to another bus stop

## Visualizations 
(1) Choropleth Charts 
<br> Adopted to display the bus stop densities across Singapore, segmented by subzones. 

(2) Chord Diagrams
<br> Adopted to display the flows between different regions/planning areas/subzones in Singapore 
<br> - These diagrams represent flows or connections between several entities (i.e. nodes). 

 For a walkthrough on the data cleaning process, as well as the data visualisations, you may head to this [Google Colab site](https://colab.research.google.com/drive/1K0IxFhGMa3sqCJjdW5cZ8qalPF7Oy2j8?usp=sharing) to explore the data on your own without needing to clone this repository.