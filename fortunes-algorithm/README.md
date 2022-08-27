# Fortune's Algorithm

This project was a final task in computational geometry course. It's main goal was implementation of Fortune's Algorithm for creating Voronoi diagrams for a given set of points on 2 dimensional plane

### Problem description

In mathematics, Voronoi diagram for a given set of points, is such a way of partitioning the plane into n sections that every point within the same section is closer to one of n given points than it is to any other out of the remaing n-1

There are several ways of tackling this problem but one of the most effective ones is Fortune's algorithm using the principle of 'sweeping' - methode of solving computional geometry problems that involves computing, solving, creating or modifying certain events while traversing the plane. In this particular example the structure called 'sweep' is not a straight line but a set of parabolas instead. For more information I recommend checking the [wikipedia](https://en.wikipedia.org/wiki/Fortune%27s_algorithm) page about the algorithm

Fortune's algorithm works exclusively for 2 dimensional plane. For 3 dimensional space different methodes must be used(such as inverting [Delunay triangulation](https://en.wikipedia.org/wiki/Delaunay_triangulation))