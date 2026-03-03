# Risk-posed-by-flooding-to-vulnerable-communities-in-Leeds
A spatial assessment of risk posed by flooding in Leeds based on the RCP 8.5 climate scenario, identifying isolated communities with limited vehicle access. Identifying elderly populations in isolated areas that are at risk to flooding.  

# Background and context
Recently, climate change has had an adverse effect on rainfall across the UK increasing the frequency and magnitude of extreme storm events such as Storm Chandra (January 2026) that brought 110mm of rainfall to parts of the UK (Met Office, 2026), and extreme flood warnings endangering vulnerable populations in UK cities (Sayers et al. 2018).

In line with the IPCC Representative Concentration Pathway 8.5 (worst case climate scenario), major flooding is set to increase with global warming, raising sea level and causing rivers to exceed water carrying capacity (Griffin et al.2022). Identifying vulnerable communities that may become isolated during major flooding is necessary, using demographic data such as elderly population percentage and access to private/public transport, higher risk populations can be identified and local governments can distribute mitigation strategies accordingly.

Population density has risen in UK cities such as Leeds, rapid urbanisation increases the risk of flooding due to the use of impermeable building materials such as concrete, and loss of greenspace, decreasing water infiltration (Rentschler et al.2023). Based on the RCP 8.5 climate scenario, a buffer around Leeds waterways aims to help local governments identify at risk areas as waterways exceed carrying capacity and exceed embankment limits (Griffin et al. 2022).

# Data Information
Ordnance Survey (2024) OS Points of Interest, POI [Geopackage] Available at: https://digimap.edina.ac.uk/roam/map/os POIs can be added to provided an extra level of information to choropleths adding context, data can be filtered to only show required data such as railways and health clinics.

Ordnance Survey (2021) Open Rivers, Leeds Rivers [Geopackage] Available at: https://digimap.edina.ac.uk/roam/map/os
The Leeds Rivers file contains a GeoPackage of the Leeds WatercourseLinks. OS Open Rivers data provides an overview of all UK watercourses however, the Leeds Rivers datafile has been clipped to contain only a ‘multilinestring’ geometry variable of Leeds river data for the creation of a future flood risk buffer.

Office for National Statistics (2011) Geoportal, OA_2011_EW_BFC [Shapefile] Available at: https://geoportal.statistics.gov.uk/datasets/417d65831892486bb88002c2e23520c1_0/explore Data retrieved contains 2011 output areas. This data provides a shape file that can be joined- using the common ‘OACD11’ column- to csv data visualising values spatially.

Office for National statistics (2011) Nomis Census Data- Age Structure, Elderly Leeds [Dataset] Available at: https://www.nomisweb.co.uk/census/2011/ks102ew This data contains elderly population (75 plus) data in a csv format that can be used to calculate percentage of elderly people per output area, this data can be visualised spatially when joined to shapefile geometry data.

Office for National statistics (2011) Nomis Census Data – Car or Van Availability [Dataset] Available at: https://www.nomisweb.co.uk/census/2011/ks404ew Car and van availability contains data per household, to help identify vulnerable communities this data contains a no car availability column that can be compared to other demographic variables such as age.

# Code Aims
- Provide clear, well thought out visualisations supported by statistical reasoning
- Help local governments identify vulnerable communities during future flood events


# References
Griffin, A., Kay, A., Sayers, P., Bell, V., Stewart, E. and Carr, S., 2022. Widespread flooding dynamics changing under climate change: characterising floods using UKCP18. Hydrology & Earth System Sciences Discussions.

Met Office (2026) Available at: Storm Chandra: How the storm unfolded and where the heaviest rain fell - Met Office (Accessed: 30/01/2026)

Rentschler, J., Avner, P., Marconcini, M., Su, R., Strano, E., Vousdoukas, M. and Hallegatte, S., 2023. Global evidence of rapid urban growth in flood zones since 1985. Nature, 622(7981), pp.87-92.

Sayers, P., Penning-Rowsell, E.C. and Horritt, M., 2018. Flood vulnerability, risk, and social disadvantage: current and future patterns in the UK. Regional environmental change, 18(2), pp.339-352.
