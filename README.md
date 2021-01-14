# HackerBotNets

A simple Jupyter Notebook used to collect data from banned IP's of botnets trying to hack my cloudcomputer.
The data is collected using iptables to lookup banned ip-numbers and then combine that data with the output of geoiplookup
to get the geographical location for that ip-number. The raw data is loaded into python with Pandas dataframes. We cleanup
the data and combine the data with real countrynames before using Geopandas to plot the data onto a world map.ython 

A easy way to get into Pythoun 3 is installing Anaconda and then use Anaconda Navigator to initialize a jupyter Notebook session if you do not prefer to do all from the cli.
