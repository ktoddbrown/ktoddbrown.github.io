---
layout: page
title: Current Projects
order: 3
---
## Data harmonization, discovery, and access

As online data repositories become more widespread, data is increasingly moving from the filing cabinets at the research lab into the public sphere.
This is a vast improvement over the data loss that frequently occurs as researchers move on or leave the field when data is left in the lab or office.
However, harmonizing this data to make it intercomparable remains an ongoing challenge.
In many data harmonization projects, data providers are asked to fill out templates that are inevitably too big (with extraneous variables/columns unrelated to their study) and too small (without a way to document some key measurement or experimental treatment).

The Soil Organic Carbon Data Rescue and Harmonization Repository (SOC-DRaHR)  takes a script-centric approach to data harmonization.
SOC-DRaHR is a centralized repository that collects scripts that to download and process data, enabling the creation of reusable and reproducible data products.
Organized by the International Soil Carbon Network, we welcome data contributions or other collaborations on this project!
Please see our GitHub repositories for further details: [https://github.com/ISCN/SOC-DRaHR](https://github.com/ISCN/SOC-DRaHR) [https://github.com/ISCN/soilDataR](https://github.com/ISCN/soilDataR)

## Process-rich soil carbon models

Most soil carbon models currently used are rooted in the idea of soil 'quality' and use first-order linear decay kinetics.
This tends to match ecosystem level observations, after a requisite tuning, but does not explicitly match the underlying processes governing soil carbon dynamics.
Process-rich models bring these governing processes from an implicit to an explicit representation.
These process-rich models have opportunities for data integration that are not possible with traditional soil quality based models.
For example, a quantified qPCR signature for a particular keystone species may be proportional to a microbial pool represented in a process-rich model.
In addition, process-rich models are frequently non-linear and require new mathematical strategies to work with.
I am developing new models to incorporate cutting edge data and concepts to inform biogeochemical projections.

## Reduced complexity soil carbon models

Once we have a soil carbon model we feel comfortable with, we can start formalizing under what conditions that model can be simplified or reduced in complexity.
My past work has shown that traditional multi-pool soil carbon models simplify to a single pool when soil inputs approximately equal soil outputs, as is the case in most well-developed soils in the field, leading to novel ways to analyze field data and compare simulation outputs.
This concept of reducing complexity becomes even more relevant when working with newer process-rich soil decomposition models.
I am currently investigating the effects of process complexity on bulk carbon dynamics under heterogeneous parameterizations and look forward to extending this to interconnected pore structure.
