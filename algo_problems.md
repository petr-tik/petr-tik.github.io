Just wanted to summarise my TILs from doing HackerRank problems up to now.

The most important skill is to remember the implemented solution and how you turned the problem into something solvable by your algorithm. eg. When you are dealing with weighted edges, but know that a breadth-first search is neccessary (test for bipartiteness), estimate the complexity and see how you can turn the graph into unweighted. 

In [this problem](https://www.hackerrank.com/challenges/beautiful-path), you need to calculate the minimum path between nodes in a weighted graph, with a custom binary operation (AND product) to calculate the overall cost of the path. This particular problems has not too many nodes, so you can create A<sub>i</sub> versions of each node, where i = 0...1024 and reconnect such A<sub>i</sub> -- B<sub>j</sub>, where j is the binary value of the decimal cost of the original edge between A and B in the first graph. Once you see that and redraw the graph, you can implement an easy bfs, which will find all paths and use each nodes index to keep track of the AND product


## Comparting Codeforces and HackerRank
Having registered on both, I wanted to write up the differences I noticed so far. 

Codeforces is more hacker-oriented, while HackerRank is a very polished product useful for recruitment and applications. Codeforces gives less information about failed tests and doesn't show testcase inputs, which makes you more focussed on your own mistakes, rather than looking up each failed testcase to see which edge case you missed. 

HackerRank has a better UI, interface that's easier to navigate to register for contests, explore different problem domains and a streamlined process for companies to organise hiring pipelines. HackerRank have a great marketing and sales team and are increasingly becoming the go-to platform for top tech and financial companies to vet already existing candidates and attract new ones with sponsored contests.

Codeforces has more thorough testcase coverage, as well as history of hosting really difficult challenges. Sponsored by Durov, as (I imagine) a recruitment platform for Telegram, it was never developed and opened up to other companies proactively and very few companies outside the ex-USSR region. The userbase is full of very strong Eastern european coders, which sets the bar very high. 

As a business, HackerRank has beaten codeforces by occupying the niche of technical tests/screen for big companies' recruitment processes, while Codeforces (as far as I know) still feeds of donations from Telegram. While we are happy Durov still has enough money to run such a website, I don't see codeforces growing outside the ex-USSR region. 
