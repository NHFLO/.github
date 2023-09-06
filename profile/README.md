## NHFLO groundwater modeling framework
This framework comprises of a set of Python scripts to create Modflow 6 groundwater models from public data and proprietary data from PWN and HHNK. Groundwater models are made using notebooks that combine Python code with text descriptions and figures. NHFLO heavily relies on [nlmod](https://github.com/ArtesiaWater/nlmod) to convert public data from Dutch sources, via [flopy](https://github.com/modflowpy/flopy), to [Modflow 6 groundwater models](https://www.usgs.gov/software/modflow-6-usgs-modular-hydrologic-model).

This organisation contains three main repositories:
- [Tools](https://github.com/NHFLO/python-NHFLO-tools). Contains the Python scripts that interprets public and proprietary data from PWN and HHNK.
- [Data](https://github.com/NHFLO/data). Contains a catalogus with metadata of the public and proprietary data source of PWN and HHNK. The repository also includes mockup data for testing purposes. This is altered such that it does not represent reality but is usable to test the tools and groundwater models.
- [Modelscripts](https://github.com/NHFLO/NHFLO_models). This is a private repository containing groundwater models used in production, in the form of Python notebooks.

## Partners
PWN and HHNK use NHFLO to model their groundwater systems. Artesia has built most of the Python scripts part of NHFLO.

### PWN
[PWN Waterleidingbedrijf Noord-Holland](https://www.pwn.nl/) is the drinkingwater company of the Province of Noord Holland. The dunes are used as a filtration step in the production of drinkingwater. 
Furthermore, PWN manages and protects the flora and fauna in these dunes, as they are listed as Natura 2000 nature reserve.

### HHNK
[Hoogheemraadschap Hollands Noorderkwartier](https://www.hhnk.nl/english) is the regional water authority of the Province of Noord Holland. They are tasked with the resposibility to prevent the land of getting flooded, sufficient availability of fresh and clean water, and road safety.

### Artesia
[Artesia](https://www.artesia-water.nl/) is a small collective of groundwater modeling consults based in Schoonhoven, the Netherlands.
