UTM system to Longtitude Latitude System:
===========

A Python script that converts NAD83 UTM Coordinates to Latitude/Longitude (WGS84).  Based on "node-coordinator" by Larry Moore.  I converted his modular JavaScript code to one Python for the sole purpose of converting UTM X,Y to Lat/Long. 

How to use it:
=====

The script is pretty simple: The function asks for Easting(X), Northing(Y) and the UTM Zone, and then outputs the longitude and latitude. 

This is based on the "node-coordinator" project by beatgammit (https://github.com/beatgammit/node-coordinator).

Motivation:
I ran into a problem will require me to use UTM coordinate system. I needed  to convert over 500K lines of UTM data to Longtitude and Latitude system. Hence, this repository exists at here.
