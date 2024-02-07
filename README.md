# openair_breath_london
This is a set of R data analytics tools for policy analysis of data from the [Breathe London network of air pollution measurement sites](https://www.breathelondon.org), and compatible with the [OpenAir suite](https://github.com/davidcarslaw/openair/blob/master/R/openair-package.R) of atmospheric science tools, funded by the UKS NERC and led by David Carslaw. 

The tools are written in the **R language** for compatibility with OpenAir, accessing data via the [Breathe London API.](https://www.breathelondon.org/developers)

## Functions included as of 9th Feb 2024

- `importBLSiteMetadata` imports the meta data for all sites in the Breathe London network database, using its API.
- `classifySitesByBorough` adds Borough and Ward metadata to the resulting list of sites, to help geolocate them for policy applications.
- `getBreatheLondonMeasurements` download the measurements from a specified set of Breathe London sites over a certain period.
- `makeOAdata` puts these data into OpenAir compatible long format.


These tools are developed by Iarla Kilbane-Dawe, and was instigated with initial project funding by the Regulatory Services Partnership of London Boroughs of Merton, Richmond and Wandsworth.
