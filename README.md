# woeplanet-data-placetypes

This repository contains records for WoePlanet (nee GeoPlanet) *placetypes*.

# The Short Version

Where On Earth (AKA WOE, AKA GeoPlanet) data, smushed up with coordinate and boundary data from Flickr Shapes, QuattroShapes and Natural Earth Data. That's fancy talk for polygons.

# The Long Version

_Forking GeoPlanet one place type at a time_.

This is an active but still experimental project to create a community-driven project to maintain and update the Creative Commons licensed GeoPlanet dataset.

Rather than create a single repository with every record the plan is to create smaller datasets organized by placetype in the hopes that they will be more manageable to download and to update by users interested in particular place types.

This repository contains _those_ placetypes, or at least the definition of what each GeoPlanet placetype _means_.

Each placetype is stored as a separate JSON file. SON was chosen because it has wide support in variety of tools, most programming languages (and specifically JavaScript), can be edited using any old text editor (or Github's own "edit this page" functionality) and allows for any number of custom key/value pairs using the GeoJSON properties dictionary.
