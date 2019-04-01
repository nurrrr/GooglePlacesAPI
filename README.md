# GooglePlacesAPI
Fetch all points of interest from GooglePlacesAPI for particular geographic region

Code creates a grid with a distance of x km between vertical or horizontal coordinates either within custom northwest-southeast square polygon or from geojson.

For every coordinate within a grid API calls are raised, with overlap results drop during data consolidation.

Points-of-Interest types can be changed based on the requirements.

Note: Make sure perform only permitted number of API calls in order not to get over-billed. Check the latest google documentation for prices and qoutas.
