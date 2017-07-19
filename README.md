# Analyzing Residential FAR Utilization in Atlanta

**Objective:**

To better understand whether zoning requirements in the City of Atlanta are restricting the level of building density per land area, or if the real estate development market actually doesn't demand higher building density and more vertical development.

The [IPython notebook](https://github.com/hannahkates/atlanta-far-utilization/blob/master/atl_far_utilization.ipynb) documents the methodology used to analyze the ratio of real built square footage on each parcel versus the total allowed square footage per parcel, according to each parcel's lot size and zoning requirements. Links to all data sources and the rendered charts are included in the notebook.

The research paper that explains the analysis and findings is [available here](https://github.com/hannahkates/atlanta-far-utilization/blob/master/HKates%20Final%20Paper.pdf).

**Limits of analysis and assumptions:**

- Only analyzed residential parcels in the City of Atlanta
- ~18% of the parcels had a null value recorded for building square footage (BldgSF). This research excluded the null entries and did not analyze analyze vacant land and parcels with BldgSF recorded < 400 square feet
- ~22% of the parcels had a lot size in square feet (LotSize) recorded as zero. This research did not analyze parcels with a LotSize recorded < 400 square feet
- Excluded all parcels that weren't residential and all parcels with complex SPI or conditional zoning
