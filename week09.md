Jack Lafond
Week 9 Reflection
CS 573
===

Link to Paper:
---
https://academic.oup.com/bib/article/13/5/627/412507

Reflection:
---
In this paper from 2011, authors Martin Krzywinski, Inanc Birol, Steven J.M. Jones, and Marco A. Marra explore a new way of visualizing networks. They explain that many networks are visualized with force-based or spectral layouts which can lead to randomness and lack reproducability. The authors explain that altough many refinements have been maid and new algorithms introduced to increase the readability and effectiveness of these network graphs, they still receive the moniker 'hairballs' because of how messy and unpredictable they can look as data sets get larger. They go on to explain that while some methods use heirarchical layouts to improve the neat-ness of the graphs, small changes like removing a connection can result in completely new graphs. In their new chart, a Hive Plot, stages/heirarchies are ordered into separate axes. The nodes belonging to these layers are plotted on the axes, can be numerical or categorical. Then the connections between nodes are drawn from these axes, and the axes are wrapped circularly to allow nodes on the last axis to connect back to the first axis (doesn;t have to be connected back if there are no connections, like if the axes were stages where the last stage did not cycle back into the first stage). They explain that this plot allows for a more neat layout that is easier to comprehend, it is robust as removing a node/edge does not effect other unconnected nodes, and the simplicity allows for faster render times. They compare this plot to a parellel coordinates plot that is radially transformed. In HPs with only 3 axes show all connections between each axis, however for plots with more than 3, not all connections betwen axes can be shown. In these cases they provide clustering algorithms to decide which axes to plot next to others (highly connected plots will be charted as neighbors so that their connections can be drawn). They also show how an axis can be split to show interconnections within that group. 
