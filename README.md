# Cambodian Gold Mine concessions in the Prey Lang Wildlife Sanctuary.

# Summary
The aim of this project is to detect gold mines that have emerged deep within the boundaries of a wildlife sanctuary. The code investigates an area of interest (AOI) in the central-southern region of Prey Lang, defined by a bounding box geometry. This approach ensures that the code is transferable to any forested area worldwide.

Timeseries of Sentinel-2 satellite imagery reveal significant visual changes (FIG 1). However, further investigation is required to determine the specific type of mining activity taking place. Mining operations in the region are well-documented by journalists, highlighting the environmental and social pressures, and revealing links between concession owners, government officials, and potential corruption. A mining concession database confirms the prevalence of gold mining in the southern part of Prey Lang, and when overlaid on a map, it shows that the AOI straddles the border of an established gold mining concession.

Figure 1
Timelapse of Sentinel 2 images showing anual changes to landuse in the AOI from 2018-2025
![AOIyear](https://github.com/user-attachments/assets/4dd4bd8b-9b27-42b2-ae3e-55470d0f5e5a)


Using the methodology outlined in Monitoring Gold Mining Activity Using SAR (Cardille et al., 2024), I detected changes through the use of Sentinel-1 SAR imagery. These images, with a resolution of 5 metres, allow for near real-time monitoring and can penetrate through clouds, making them highly suitable for rainforest environments. Timeseries change detection with radar imagery can thus be applied year-round, complementing the optical imagery. SAR imagery is particularly effective for detecting changes in soil structure and moisture content, which are key indicators of gold mining activity. This is due to the use of water in extraction processes, the accumulation of chemical pools, and the significant land deformation that typically accompanies such operations.

The results indicate that gold mining activity was detected in the area in 2024 (FIG 3). This increase in activity may be linked to the surge in gold prices during that year. Nevertheless, the detected changes, even prior to post-processing, clearly show alterations in the mining pits over the three years they have been operational. Furthermore, smaller artisanal operations may be responsible for the detections observed outside the main pits. Further on-the-ground research is needed to corroborate these findings and refine the environmental filters in post-processing for more accurate results.

Alternatively, the results suggest an absence of hydraulic gold mining, concluding that, while these mines are causing similar environmental destruction and providing access for illegal loggers, they may be less environmentally damaging compared to other methods of mineral extraction.

I am currently monitoring a known gold mining site to the west of the AOI to determine the optimal thresholds for the filters to be applied during post-processing of the Sentinel-1 timeseries mosaic. This will aid a more definative answer, and help the accuracy of 


## Splitmap

<iframe src="AOIsplitmap.html" width="100%" height="500px"></iframe>
