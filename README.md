# VoCC_data_sets
Companion data sets to the VoCC package vingette "VoCC_Tutorial" for reproduction of examples in Garcia Molinos et al. 2019 MEE. The data folder contain the following data sets.

# 1. HSST: Global monthly mean sea surface temperatures (SST) for 1955-2010.
A raster stack with 672 layers containing global mean monthly SSTs (HadISST 1.1) at 1-deg resolution for the period Jan 1955 to Dec 2010. Sourced from the Hadley Centre https://www.metoffice.gov.uk/hadobs/hadisst/ (accessed May 2018).

Rayner et al. 2003. Global analyses of sea surface temperature, sea ice, and night marine air temperature since the late nineteenth century. J. Geophys. Res.Vol. 108: 4407. https://www.metoffice.gov.uk/hadobs/hadisst/HadISST_paper.pdf


# 2. EEZs: Western Pacific tropical Exclusive Economic Zone (EEZ) boundaries.
A spatial polygon data frame containing EEZs for Western Pacific tropical island nations sourced from http://www.marineregions.org/downloads.php (v10).

# 3. Global metadataset of reported marine species range shifts.
An extract from the meta data set provided used by Poloczanska et al.(2013) containing range shifts in marine taxa reported in the literature. This data set corresponds to the most updated version as provided in Brown et al.(2016). Following the original analysis, null responses have been removed and shifts reported as absolute shift distances. See Poloczanska et al. (2013) for details.

Poloczanska et al. 2013. Global imprint of climate change on marine life. Nat. Clim. Change, 3, 919-925. https://www.nature.com/articles/nclimate1958

# 4. Climate velocity trajectories
Climate velocity trajectories produced using the HSST data for a starting 0.25-degree coordinate grid and the period 1960-2009. The data frame contains coordinates and id for each trajectory.


