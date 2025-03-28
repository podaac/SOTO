# State of the Ocean (SOTO)

![PlantUML model](http://www.plantuml.com/plantuml/svg/5SoniS8m30RW_atn621MJvKDKi02GjOHtyMIJ_wLh0zKN_Uj4np8VlpTcicHLVztOCmxKV1LtWrxld9gY1lKKCGx3Q_CGe_jkL7dPZGTlepmceB5JuspwLN6hrtLwjSF)

This open source product line from JPL's [PO.DAAC](https://podaac.jpl.nasa.gov/) and [NASA's EOSDIS](https://www.earthdata.nasa.gov/eosdis) is an interactive, web-based tool to generate informative maps and animations that communicate and promote the discovery of the state of the ocean.

SOTO is a suite of tools presented through an interactive, web-based visualization front-end. It provides access to a broad range of satelite-derived products and key parameters of interest to the oceanographic community. SOTO facilitates visual exploration and the ability to download data to analyze with your own tools enabling your research. Many of the imagery layers are updated daily and are available within three hours of observation - essentially showing the entire Earth as it looks "right now". Arctic and Antarctic views of many products are also available for a "full globe" perspective. Geostationary imagery layers are also now available. These are provided in ten minute increments for the last 90 days. These full disk hemispheric views allow for almost real-time viewing of changes occurring around most of the world. Browsing on tablet and smartphone devices is generally supported for mobile access to the imagery.

## Related Repositories

In addition to the web tool, SOTO consists of a number of supporting backend components as well. Development on the individual components of the system is handled within each respective repository. Planning and documentation for the system as a whole is concentrated in this repository.

Component repositories:
- https://github.com/podaac/worldview
- https://github.com/podaac/bignbit
- https://github.com/podaac/net2cog
- https://github.com/podaac/netcdf_to_geojson_vectors
- https://github.com/podaac/gibs-imagestat
- https://github.com/podaac/hydrocron
- https://github.com/podaac/feature-translation-service/
