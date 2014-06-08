UK Postcodes
============

This repository contains a CSV of UK postal out codes. It contains some mappings to English
regions that were not on the original.

It is not clear whether the Latitude and Longitude coordinates use the Airy or the WSG85 Ellipsoid
and datum. An action to find out and make it clear as necessary. TRhe WSG85 coordinates will
ultimately be in this set.

Some notes on the columns:

* postcode The outward part of the postcode.
* eastings The numeric eathing value (whole metres from the false origin, up to 7 digits)
* northings The numeric northing value (whole metres from the false origin, up to 7 digits)
* latitude The latitude angle in degrees.
* longitude The longitude angle, in degrees.
* town The town or city.
* region The county or municiple region or city conurbation.
* country The country code.
* country_string The name of the country.


For the original source, see:
http://www.dangibbs.co.uk/journal/free-uk-postcode-towns-counties-database
