# Social Networking Analysis with networkx: IS434 Topic Sharing

Social Networking Analysis demo using Python library [networkx](https://networkx.org/) with simulated simplified [World of Warcraft](https://worldofwarcraft.com/en-us/) player location data. The graph illustrate the closeness between any two players using edges and their weights. Clusters of players close together can be identified.

## Requirements 

Requirements for building and running this demo:

- [Python 3.9](https://anaconda.org/anaconda/python/files?sort=distribution_type&sort_order=desc&version=3.9.7)

## Data description

The csv file [wow_data.csv](https://github.com/Royaladvisor26/SNA_WOW/blob/main/wow_data.csv) contains 30 rows of data for 30 simulated players. The data consist of 4 columns: playerID (ID of the player), infect_status (whether the player is infected or not), lat (the latitude of the player's position), lon (the longitude of the player's position)

## Running the demo

Open [social network analysis WoW.ipynb](https://github.com/Royaladvisor26/SNA_WOW/blob/main/social%20network%20analysis%20WoW.ipynb), select Cell->Run All. You should be able to see the final [networkx](https://networkx.org/) illustration at cell block [14]

## Troubleshoot

### ModuleNotFoundError in Jupyter

If you encounter such error message `ModuleNotFoundError: No module named 'package_name`, try inputting this command in a code block

```python
!pip install package_name # replace package_name with the name of the missing package
```