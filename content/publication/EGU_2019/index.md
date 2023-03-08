---
url_pdf: https://meetingorganizer.copernicus.org/EGU2019/EGU2019-18010.pdf
publication_types:
  - "1"

abstract: The present study proposes and exemplifies a methodology to estimate the carbon stock from aerial biomass.
Essentially, the method combines field data from forest inventory to obtain site specific measurements of carbon
stock, and airborne LiDAR (ALS) data to derive proxy variables of forest structure. We then model and spatialize
carbon predictions.
First, we filtered forest inventory plots to retrieve those representing ‘pure’ forest stands, i.e. dominated by a
single species (above 80% of individuals belong to the same species). Next, carbon stock was calculated from
biomass estimations based on dasometric measurements in the plots. A set of ALS-related variables were then
calculated extracting ALS data on plot sites. Finally, specific Random Forest models (one per species) were fitted
to establish the relationship between aerial carbon (response) and ALS data (predictors). The models were applied
to the entire study region of Catalonia, Spain. Information on species presence (retrieved from the Spanish Forest
Map as canopy cover) was used in the process so that each pixel in the region was assigned a weighted sum of
aerial carbon according to the species coverage.
The procedure was applied in Catalonia (Northeast of Spain), a region dominated by Mediterranean-type forests.
We used the 4th National Forest Inventory (2016) and ALS data from the National Plan of Aerial Orthophotography
(0.5 points m-2; 2016-17). The most frequent species were Pinus halepensis (N=804), Pinus nigra (N=275),
Pinus sylvestris (N=501), Quercus suber (N=118), Quercus ilex (N=393) and Quercus pubescens (N=118), thus in
this example only these species were retained from inventory plots. ALS data consisted of: Canopy cover, Canopy
Relief Ratio, height mean, height standard deviation, height kurtosis, height skewness, 99th percentile, slope
aspect, elevation and slope. Three models were fitted for each species apiece, randomly resampling the original
data to apply a k-fold (k=3) cross-validation (CV) procedure. The adjusted R2 values obtained from CV ranged
from 0.82 in Quercus suber to above 0.9 in Pinus communities (Pinus halepensis 0.9, Pinus nigra 0.91, Pinus
sylvestris 0.93). Other Quercus species obtained R2 around 0.87 (Quercus ilex 0.86, Quercus pubescens 0.87).
authors:
  - admin
  - marcos-rodrigues
  - aitor-ameztegui
  - cristina-vega
url_dataset: ""
url_project: ""
publication_short: In *EGU - General Assembly*
url_source: ""
url_video: ""
publication: In *European Geosciences Union*
featured: false
date: 2019-04-28T00:00:00.000Z
url_slides: ""
title: " An assessment of aerial carbon stock combining forest inventory data
  with LiDAR-derived canopy and topography metrics"
image:
  caption: ""
  focal_point: ""
  preview_only: true
publishDate: 2021-03-01T00:00:00.000Z
url_poster: Poster.pdf
url_code: ""
doi: ""
---
