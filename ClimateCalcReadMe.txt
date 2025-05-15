CME 15 May 2025

- Decided to look into meteorological calculations to see if I could create a climate table similar to the ones found on many city Wikipedia pages.
- starting with site USC00105414 near Lowman, ID, which has a wiki page but not a climate summary table
- went through the NOAA NCEI data search page at https://www.ncei.noaa.gov/access/search/index
- using the daily summaries GHCN-Daily version 3 https://www.ncei.noaa.gov/access/search/data-search/daily-summaries
- just typed in the location and there's only one available site (USC00105414 for Lowman, ID)

- Nevermind. I searched around a bit more and found the US Climate Normals Product Suite (1981 - 2010)
- https://www.ncei.noaa.gov/metadata/geoportal/rest/metadata/item/gov.noaa.ncdc:C00820/html
- pulled these data for Lowman directly (same USC00105414 code, different headers and different date column)
- created a cleaned version with just the columns of interest
- note that temperatures are in tenths of a degree Fahrenheit

- can always use this link and adjust the USC code number:
https://www.ncei.noaa.gov/access/services/data/v1?dataset=normals-monthly-1991-2020&stations=USC00105414&format=pdf&dataTypes=MLY-TMAX-NORMAL,MLY-TMIN-NORMAL,MLY-TAVG-NORMAL,MLY-PRCP-NORMAL,MLY-SNOW-NORMAL

- and this link is helpful for climate extremes:
https://xmacis.rcc-acis.org/ (station LOWMAN)