# /Airports/EGxx/Basic.txt
# What are they?
The basic definition of an airport including center point (used by .center) and base frequency (unused). 

# How to format them
These definitions go into the .SCT file. 

    <airport identifier> <frequency> <North coordinates> <South coordinates> E ; <Airport name>

   E.g

    EGNX 119.650 N052.49.52.000 W001.19.41.000 E ; East Midlands

The source Basic.txt definition (found at Airports/EGNX/Basic.txt) is defined as below:

    <airport name>
    <Coordinates>
    <frequency>
   E.g. 

    East Midlands
    N052.49.52.000 W001.19.41.000
    119.650

The coordinates follow standard EuroScope coordinate formatting.

# Where to find them
Position information can be found by searching the .SCT file for the airport ICAO. E.g. 'EGNX'

# Reference
Reference documentation can be found in the [Euroscope Documentation](https://www.euroscope.hu/wp/ese-files-description/).