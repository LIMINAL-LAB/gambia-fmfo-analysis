# Monitoring Fishmeal & Fish Oil production near Gunjur (The Gambia) with 3m PlanetScope Imagery: An Exploration

In recent years, the waters off West Africa have become a crucial component in the increasingly globalized fishing industry, supplying farms and consumers throughout Asia, the Americas and Europe with the region’s most vital staple: fish. 
A process of acute extraction, orchestrated through an increasing number of foreign fishing fleets, obtaining access to West Africa’s abundant marine ecology through political agreements as well as illegal fishing practices.

This preliminary study focuses on in the Gambian coastal village of Gunjur, where the Golden Lead FMFO factory opened in 2016. 
The study employs remote sensing techniques to detect the presence of artisanal fishing vessels gathering to land their catch in the Bay of Gunjur during the 6 months of FMFO factories activity, between November and June. 
This framework allows for the study of changes in the activities and numbers of artisanal fishing brought about by the factory’s operations. 
Whilst providing insights into practices of temporary migration between Senegal and The Gambia driven by FMFO production. 

This repo contains our analysis of [PlanetScope](https://earth.esa.int/eogateway/missions/planetscope) satellite imagery and a report of the study that outlines our methodology and findings. 
The detection approach uses a simple, auditable NDWI-based water masking technique combined with connected components analysis, deliberately avoiding black-box machine learning models to ensure transparency and manual validation of results.

- **Detection Workflow.ipynb** - The main Jupyter notebook implementing a 9-step boat detection workflow using NDWI thresholding and connected components analysis.
- **report.pdf** - Our report documenting the analysis and describing our methodology.
