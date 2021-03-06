# README
This is a Python-based application that takes in historical weather data from winter 2017/2018 and elevation data taken by NASA's Shuttle Radar Topography Misson (SRTM). The program then creates a risk analysis of any region in the greater Salt Lake City area on any date in the winter season. It contains a command line GUI for the user to input the name of the area along with four latitude and longitude bounds and outputs an interactive 2D and 3D map for the user to see where the safest area is to ski. 

The engine of this program is broken up into three separate parts. Part one works on taking elevation data given from the SRTM and finding the specific angle of every 40-meter section of the region. Part two creates a snowpack model, an evaluation of each layer of snow, by using the Scipy ordinary differential equations module in addition with all the weather data for all days starting from the beginning of the season. The third part of this engine cross-references the snowpack model with the specific angle at each point. This part then adds an extra stress variable for a skier going down the face of the region. From this data, the specific risk of an avalanche from a skier can be found.

Updates for this program will be coming. These updates will include global historical data so the program can be run anywhere without limitations. In addition, a gradient risk analysis will be implemented for a better user experience.


This repository contains my projects. These projects are under exclusive copyright: © 2018 Patrick Schulz. All rights reserved.
