https://dl.acm.org/doi/pdf/10.1145/3544548.3580734

For this week I investigated "Interactive Context-Preserving Color Highlighting for Multiclass Scaterplots".
I was interested in this article because of doing a tooltip based project in the past, and was interested in other ways to emphasize information.
This paper's main consideration is contrast, with all the colors in the graph, with the background, and with the highlighted form/non highlighted form.
It proposes a method of having multiple color palettes and mixing them for displaying highlights.
It make sures the colors in each palette are of the same type, and has the version not being higlighted as a more warshed out version of the other.
One cool thing about their findings is that it could be extended to many different colored graph types, being more effective on stationary graphs.
Their method, unlike state of the line machine learning tools, is formulaic, so it's on the easier side for implementation.
There user study was very extensive, which is something to learn from. Measured many things like error in choosing the color, how many classes can be distinguished, etc. The more that's tested the better.
I can take from these findings a method of contrasting colors, especially for highlighting. While I don't think I'd implement a complicated equation like this one, I'd like to follow the results of this paper by introducing an alternative palette or lightening up colorings.
