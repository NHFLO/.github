## NHFLO groundwater modeling framework
This framework comprises of a set of Python scripts to create Modflow 6 groundwater models from public data and proprietary data from PWN and HHNK. Groundwater models are made using notebooks that combine Python code with text descriptions and figures. NHFLO heavily relies on [nlmod](https://github.com/ArtesiaWater/nlmod) to convert public data from Dutch sources, via [flopy](https://github.com/modflowpy/flopy), to [Modflow 6 groundwater models](https://www.usgs.gov/software/modflow-6-usgs-modular-hydrologic-model).

This organisation maintains three main repositories:
- [Tools](https://github.com/NHFLO/tools). Contains the Python scripts that interprets public and proprietary data from PWN and HHNK.
- [Data](https://github.com/NHFLO/data). Contains a catalogus with metadata of the public and proprietary data source of PWN and HHNK. The repository also includes mockup data for testing purposes. This is altered such that it does not represent reality but is usable to test the tools and groundwater models.
- [Models](https://github.com/NHFLO/models). This is a private repository containing groundwater models used in production, in the form of Python notebooks.

The modeling framework can be accessed via the [codespaces repository](https://github.com/NHFLO/codespaces). It provides an online version of VS Code (alternative to Spyder or PyCharm) preconfigured so that you can directly run the models.

[![Models](https://github.com/NHFLO/models/actions/workflows/ci.yml/badge.svg)](https://github.com/NHFLO/models/actions/workflows/ci.yml) [![Data](https://github.com/NHFLO/data/actions/workflows/build.yml/badge.svg)](https://github.com/NHFLO/data/actions/workflows/build.yml)

## Partners
PWN and HHNK use NHFLO to model their groundwater systems. Artesia has built most of the Python scripts part of NHFLO.

### PWN
[PWN Waterleidingbedrijf Noord-Holland](https://www.pwn.nl/) is the drinkingwater company of the Province of Noord Holland. The dunes are used as a filtration step in the production of drinkingwater. 
Furthermore, PWN manages and protects the flora and fauna in these dunes, as they are listed as Natura 2000 nature reserve.

### HHNK
[Hoogheemraadschap Hollands Noorderkwartier](https://www.hhnk.nl/english) is the regional water authority of the Province of Noord Holland. They are tasked with the resposibility to prevent the land of getting flooded, sufficient availability of fresh and clean water, and road safety.

### Artesia
[Artesia](https://www.artesia-water.nl/) is a small collective of groundwater modeling experts based in Schoonhoven, the Netherlands.

##
![image](https://github.com/NHFLO/.github/assets/11296133/967bf417-53df-491e-a6c1-efd75f5e48c3) 
![image](https://github.com/NHFLO/.github/assets/11296133/ee9c5137-437f-4924-b6c7-aee8bca86f4d) 
![image](https://github.com/NHFLO/.github/assets/11296133/890e0c59-1d74-44f2-8b26-b8c41622435c)
