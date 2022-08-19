# An Exploratory Analysis of Singapore's Public Bus Data 
<div style="text-align: center;">

![bus image](https://github.com/aanghs22/gitnetwork/blob/main/Images/bus%20image.jpeg?raw=true)

</div>

<div align="center">
<br> <i> Image credits: Land Transport Guru </i>
</div>

## Introduction  
As a frequent user of the public transportation system in Singapore (especially the buses), I often find myself wondering about the transportation system - is the load of commuters _always_ this heavy for all bus services? Where do people like to go via the public bus? Is there a neighbourhood that relies greatly on the buses to arrive at their destination? 

### Project Objectives 
In this project, I explored the publicly available datasets on buses with the intention of: 
<br> (1) gaining a better understanding of how people utilise the public buses to move from place to place, 
<br> (2) identifying dead zones in Singapore (areas least accessible by bus), and 
<br> (3) simply exploring the dataset. 

## Resources needed for this exploration
### Requirements: 
The requirements.txt file contains libraries that this Python notebook will depend on, and can be installed using:

```
    pip install -r requirements.txt
```
### The datasets used include: 
<br> (1) Master Plan 2019 Planning Area
- Segments the land area of Singapore into 3 different levels - Region, Planning Area and Subzone

(2) Bus Stops Dataset (from [LTA Datamall](https://datamall.lta.gov.sg/content/datamall/en.html))
- Provides the bus stop code and geo-coordinates for every bus stop in Singapore 

(3) Origin-Destination Passenger Volume Trip Records (from [LTA Datamall](https://datamall.lta.gov.sg/content/datamall/en.html))
- Sums the total trips from one bus stop to another bus stop

## Data Exploration
### Visualizations  
(1) Choropleth Charts 
<br> Adopted to display the bus stop densities across Singapore, segmented by subzones. 

(2) Chord Diagrams
<br> Adopted to display the flows between different regions/planning areas/subzones in Singapore. 
- These diagrams represent flows or connections between several entities (i.e. nodes). 
- Each fragment is represented by a fragment on the counterpart of the circular layout.
- Links are drawn between each of the entities. The size of the links correlate with the importance of flow between the entities. 

## Conclusion 
For a walkthrough on the data cleaning process, as well as the data visualisations, you may head to this [Google Colab site](https://colab.research.google.com/drive/1K0IxFhGMa3sqCJjdW5cZ8qalPF7Oy2j8?usp=sharing) to explore the data on your own without needing to clone this repository.

## Acknowledgements
I would like to thank Shaun Khoo for his guidance on this exploratory project that I embarked on in the summer of Year 1. 