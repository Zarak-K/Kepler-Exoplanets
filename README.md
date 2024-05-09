This Jupyter Notebook uses the Python module Lightkurve to extract data from an opensource databank containing lightcurves for targets of the Kepler and K2 mission.
Lightkurve is also able to access data from the more recent TESS mission, so the notebook can easily be adjusted to access either.

These missions use the transit method to identify exoplanet candidates around host starts. By identifying periodic dips in the flux of a star, the presence of an exoplanet can be inferred assuming the magnitude of the dip is in proportion to what would be expected for a planet passing in front of a star. For example, as Jupiter transits the Sun, we would expect to see a ~1% dip in flux. Significantly larger dips can be indicative of eclipsing binary systems, but their detection was not the primary focus of these missions.

The sizes of these exoplanets can also be estimated from the magnitude of dips in flux. From the sizes, a rough categorization of the planet into either rocky terrestrial or gas giant can be performed. 
Rocky terrestrial planets are of great interest when considering habitability, especially for targets of the TESS mission which are much closer to our solar system.
