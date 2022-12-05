## Network visualization (chord diagram) in Flourish

### Description
Chord diagrams are a kind of network visualization. They show interconnections between entities in a closed system, meaning that all of the entities are connected to each other at least once. This kind of network does not show directionality very well, and it is not optimal for showing connections between a large number of entities, because it can get visually confusing and too complex to easily parse.

An example of a historical chord diagram visualization is an ["Interactive Chord Diagram of Katherine Dunham’s Dancers, Drummers, and Singers, 1947-60"](https://www.dunhamsdata.org/portfolio/visualizations/interactive-chord-diagram) which highlights the connections between people associated with Katherine Dunham, a prominent 20th century dancer and choreographer. I believe this visualization used a tool called Gephi.

Another cool example which was definitely made with Gephi is ["Linked Jazz."](https://linkedjazz.org/network/)

### Directions

#### Making a dataset suitable for showing connections between entities
I will walk you through my process of creating a small dataset from information on the [Founders Online website](https://founders.archives.gov/) to create a Founders Online [chord diagram visualization.](https://public.flourish.studio/visualisation/3641990/)

The data is at [https://hist5152.github.io/fall22/FoundersOnlineNetworks.csv](https://hist5152.github.io/fall22/FoundersOnlineNetworks.csv)

- Meet me at [the overview](https://app.flourish.studio/@flourish/chord-diagram/3) to review the data this chart needs and what it will look like.


#### Questions to keep in mind when working with historical data and network visualizations of all kinds: 

- How is the data structured? How might it differ for another kind of visualization?
- What additional questions do you have about the individuals who will be represented as nodes?
- What contextual knowledge is needed to interpret this network of connections?
- Are there gaps, silences, or alternative networks that are not accounted for in the data?


More complex networks:
- [Flourish template](https://app.flourish.studio/@flourish/network-graph/10)
- [Programming Historian tutorial "From Hermeneutics to Data to Networks: Data Extraction and Network Visualization of Historical Sources"](https://programminghistorian.org/en/lessons/creating-network-diagrams-from-historical-sources)

