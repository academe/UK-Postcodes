UK Postcodes
============

This repository contains a CSV of UK postal out codes. It contains some mappings to English
regions that were not on the original.

It is not clear whether the Latitude and Longitude coordinates use the Airy or the WSG85 Ellipsoid
and datum. An action to find out and make it clear as necessary. TRhe WSG85 coordinates will
ultimately be in this set.

Some notes on the columns:

* postcode The outward part of the postcode.
* easting The numeric eathing value (whole metres from the false origin, up to 7 digits)
* northing The numeric northing value (whole metres from the false origin, up to 7 digits)
* latitude The latitude angle in degrees.
* longitude The longitude angle, in degrees.
* city The town or city.
* county The county or municiple region or city conurbation.
* country_code The country code - three letter.
* country_name The name of the country.
* iso3166-2 The ISO country code.
* region_code The region code (non-official).
* region_name The region name.

England is divided into the following regions:

*	North East
*	North West
*	Yorkshire and the Humber
*	East Midlands
*	West Midlands
*	East of England
*	London
*	South East
*	South West

These are detailed here:
http://en.wikipedia.org/wiki/Regions_of_England

For the original source, see:
http://www.dangibbs.co.uk/journal/free-uk-postcode-towns-counties-database

There are many postcodes listed without a town or region. There are also some towns or cities
that are not accurate or are ambiguous, since a postcode can span more than one town. No attempt
is being made to clean up these two aspects at this time. My main concern was mapping cities,
regions and postcodes to a grid reference for a job board, so people can search for jobs within
a radius of a given point (the job seeker's postcode or town).

