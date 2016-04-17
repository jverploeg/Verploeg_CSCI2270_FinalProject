# Verploeg_CSCI2270_FinalProject
Extension of Dijkstra's shortest path algorithm.
I plan to work alone on the final project, so the only team member is Jack Verploeg.  The project I plan on creating is an extension of Assignment 11 with Dijkstra's shortest path algorithm. 

The idea of my project is to use several shortest path calculations to find the most efficient shopping path/route among stores in Boulder.  Building off of the structure of Assignment 10/11, I will create a text file adjacency matrix of 10-15 stores in Boulder and their distances between each other and from "Home", and another text file of what items each store carries.  Each store can carry up to 3 different items, and there will be roughly 10 total items.  The idea is that the user inputs the items they have on their "shopping list", and a path is calculated from store to store to get each item by traversing the smallest distance. So say you want to buy Item A, B, and C.  A shortest path route will be calculated for each individual item, and then those will be cross-referenced with each other( if Item A is the shortest initial distance, do you go get item B or item C next?)  Do any stores carry multiple items from "the list"?  If a store carries multiple items on the list but is farther away, would it be shorter to get those items individually from closer stores?

Obviously this is just a rough idea of the direction I want to head with the project, if it doesn't meet the requirements I will add more features.

