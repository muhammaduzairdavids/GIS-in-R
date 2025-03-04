# The Data
Note that all the data used in this project is made available in both `.csv` and `.geojson` format.

# 1. The Observation Data
The iNaturalist observation data is specifically limited to observations of Cape Fur Seal carcasses which were observed no earlier than 5 August 2025 - currently the 
earliest known date for seal rabies outbreaks. I have made this data available in both `.csv` and `.geojson` format for those interested. The `.csv` file also contains
the metadata of the observations.

To download or view the iNaturalist observation data click [`seal_dead.csv`](https://github.com/muhammaduzairdavids/GIS-in-R/blob/main/data/seal_dead.csv) or 
[`seal_dead.geojson`](https://github.com/muhammaduzairdavids/GIS-in-R/blob/main/data/seal_dead.geojson).

# 2. The Cape Fur Seal Colony Data
The seal colony data was compiled using a combination of information from Kirkman *et al.* (2012) and Maja (2024), some colonies were also included by myself based on
observations I made while checking whether the location data from Kirkman *et al.* (2012) was correct in Google Earth. It should be noted that I only added colonies
from the Maja (2024) report if the report strictly stated that samples were collected from a "colony".

The colony data is available as [`data_colony.csv`](https://github.com/muhammaduzairdavids/GIS-in-R/blob/main/data/data_colony.csv) and 
[`seal_colony.geojson`](https://github.com/muhammaduzairdavids/GIS-in-R/blob/main/data/seal_colony.geojson).

# 3. The rabies outbreak data
Unfortunately, the data on seal rabies outbreaks are not yet openly available to the public, so I had to compile my data using information obtained from the 2024 
government report by Mpho Maja. The information of the report contained only broad locality data for where rabies samples had been collected, and therefore the data 
I compiled can only do the same. I have mostly tried to pinpoint nearby beaches and areas close to the ocean as possible locations for where the data was collected, 
but instead of looking at this data set as a definite fact, consider it a simulation of what the actual data may look like.

To find this data click [`data_rabies.csv`](https://github.com/muhammaduzairdavids/GIS-in-R/blob/main/data/data_rabies.csv) or 
[`seal_rabies.geojson`](https://github.com/muhammaduzairdavids/GIS-in-R/blob/main/data/seal_rabies.geojson).

# References
Kirkman, S.P., Yemane, D., Oosthuizen, W.H., Meÿer, M.A., Kotze, P.G.H., Skrypzeck, H., Vaz Velho, F. and Underhill, L.G. (2012). Spatio-temporal shifts of the dynamic Cape fur seal population in southern Africa, based on aerial censuses (1972-2009). Marine Mammal Science, 29(3), pp.497–524. doi: https://doi.org/10.1111/j.1748-7692.2012.00584.x.

Maja, M. (2024). Rabies in Cape fur seals: outbreak update report. Department of Agriculture, Land Reform and Rural Development. Available at: https://www.dalrrd.gov.za/images/outbreaks/Rabies/2024/rabies-in-seals_dalrrd-report_oct2024_final.pdf.
