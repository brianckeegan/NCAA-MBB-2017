# NCAA-MBB-2017
Quick-and-dirty network analysis of the 2017 NCAA Men's Basketball tournament.

The data were scraped from [sports-reference.com](http://www.sports-reference.com/).

Take-away hairball visualized in [Gephi](https://gephi.org/). Nodes are teams, connected by directed edges if *i* beat *j*. Edges are weighted by the cumulative point differential (adding the point differentials if *i* beat *j* more than once). Nodes are colored by Gephi's modularity-based community detection algorithm.

![](https://github.com/brianckeegan/NCAA-MBB-2017/blob/master/tournament_wins.png)
