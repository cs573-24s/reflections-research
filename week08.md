Jack Lafond
Week 8 Reflection
CS 573
===

Link to Paper:
---
https://www.researchgate.net/publication/332220768_Orthogonal_Voronoi_Diagram_and_Treemap

Reflection:
---
In this paper researchers Yan-Chao Wang, Feng Lin, and Hock-Soon Seah, explore a new strategy for visualizing hierarchical data that blends the benefits of the rectangular treemap with a voronoi treemap. Visualization with a regular treemap divides an area into its subsections based on some value (encoding the value with the area). These subsections can be further divided as the a hierarchy has more levels. The use of rectangles make the treemap neat and tidy. In Voronoi treemaps instead decide specific sites in a canvas, and then partition that canvas into polygonal cells based on the distances to each site. These polygons can be iteratively changed as the sections are divided further into subsections, or as hierarchies change. In their new visualization, the orthogonal voronoi diragram, they blend the neat-ness and ability to compare areas of the regular treemap, with the adaptability to change of a voronoi treemap. In this new model they chose sites beforehand like in a voronoi, however to calculate the orthogonal shapes, they use what they call a sweepline and skyline. The skyline stores the caluclated boundaries, while the sweepline traverses over the sites and calculates the new boundaries to add to the skyline. They use newly defined distance functions in order to either vertically, or horizontally separate sites, resulting in orthogonal polygons. They found that their new algorithm is of time complexity O(n * log(n)). They conclude that there are some drawbacks, as inital updates can lead to layout instability, but their algorithm is as fast as the voronoi treemap, provides the benefits of the voronoi where changes do not completey change the map, and they provide the benefits of the regular treemap where cells are nested more neatly.
