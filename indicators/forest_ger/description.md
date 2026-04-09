## Tree cover loss

Tree cover loss maps is a forest loss monitoring tool built on Sentinel-1 SAR (Synthetic Aperture Radar) satellite data, processed through the SAGRIS production system (https://www.sagris.eu). <br>

The tool detects and maps tree cover loss across Germany. It captures all causes of forest loss, including natural tree death from old age, storm damage, forestry maintenance, and — most importantly — both legal and illegal timber harvesting. <br>

The maps uses SAR data. Unlike optical satellites (which are blocked by clouds), Sentinel-1 uses radar, meaning it can penetrate cloud cover and collect data year-round. <br>
<br>
The colored patches on the Forest Loss Coefficient map represent the Forest Loss Coefficient — coefficient values indicating tree loss per pixel, expressed as a percentage. Values are calculated for every pixel separately, ranging from 50% to 100% tree loss within that pixel.
<br>
For Germany specifically, forest loss is calculated only within areas classified as forest in the CORINE 2018 land cover dataset — meaning the analysis is bounded to officially mapped forest zones rather than any tree-covered area. The detection resolution is 100 m², making it far more sensitive than CORINE — however, CORINE forest boundaries are used as a coarse mask to define the analysis area.
In short, this is a near-real-time deforestation and forest disturbance early warning tool, capable of detecting small-scale changes across an entire region through all weather conditions.
