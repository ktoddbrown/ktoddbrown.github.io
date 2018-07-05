# Who am I

I am a computational biogeochemist who uses mathematics and computers to understand how soil breaths.
Soils are a major source of natural carbon dioxide (the greenhouse gas driving current climate change); soils are expected to emit more carbon dioxide as climate gets warmer, potentially creating a vicious feedback cycle.
By using data from multiple world-wide studies and simplifying or expanding the complexity of soil models to interoperate that data, I strive to give society a better understanding of this critical climate response.

I am passionate about data and open reproducible science.
As we continue to move towards data-rich research, informatics skills to archive, increase discoverability, and harmonize different data streams becomes more and more important.
Through my work with the International Soil Carbon Network, I’m working with collaborators across the global to address harmonization issues in soils.

I am a Distinguished Linus Pauling Postdoctoral Fellow at the Pacific Northwest National Lab, a United States Department of Energy laboratory in Richland, Washington (2015-2018). I have been a Postdoctoral Researcher at the University of Oklahoma (2014). I received my PhD (2013) from the University of California, Irvine from the Earth System Science Department. I also hold a Bachelor of Science (2004) from Harvey Mudd College in Claremont, California in Mathematics and I have worked as a software developer for bioinformatics tools at Massachusetts General Hospital in Boston, Massachusetts.

# What I Do (I can make this bigger or smaller as needed)

_Earth system science_ – The intersection between climate and the environment is particularly relevant as the world to respond to anthropogenic greenhouse gas emissions. Climate models provide the best insights into the effects of increases in greenhouse gas on regional climate patterns. I work with the latest Earth system models to examine future climate implications on the environment.

_Soil science_ – In particular, soil is a critical societal resource that response to local environmental changes. Soil organic carbon is expected to convert to atmospheric CO2 faster under warmer and, generally, wetter climates. This has the potential to increase atmospheric carbon dioxide levels, which in turn exacerbates climate change, creating a vicious feedback. Lower soil organic carbon levels will also negatively affect water retention and nutrient content of soils. I specialize in soil carbon dynamics and the soil-climate interaction.

_Informatics_ – Data is undergoing an explosion. Organizing, preserving, and visualizing ever increasing data is an ongoing challenge. I help manage and utilize community archives to help data live on.

_Mathematics_ – Mathematical models capture scientific understanding in such a way that it is directly testable with data. We can help translate science into mathematics using discrete and continuous mathematics to articulate your hypotheses and extend the implications over simulated space/time.

Education – Informatics and computational training has become critical for any bench and field scientist. I am a certified Software and Data carpentry instructor and passionate about open and reproducible science.

# Current projects

## Data harmonization, discovery, and access

As online data repositories become more widespread data is increasingly moving from the filing cabinets at the research lab into the public sphere.
This is a vast improvement over the data loss that frequently occurs as researchers move on or leave the field when data is left in the lab or office.
However, harmonizing this data to make it intercomparable remains an ongoing challenge.
In many data harmonization projects data providers are asked to fill out templates that are inevitably too big (with extraneous variables/columns unrelated to their study) and too small (without a way to document some key measurement or experimental treatment).

The Soil Organic Carbon Data Rescue and Harmonization Repository (SOC-DRaHR)  takes a script centric approach to data harmonization.
SOC-DRaHR is a centralized repository that collects download and processing scripts to enables the creation of reusable and reproducible data products.
Organized by the International Soil Carbon Network, we welcome data contributions or other collaborations on this project!
Please see our GitHub repositories for further details: https://github.com/ISCN/SOC-DRaHR https://github.com/ISCN/soilDataR

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
This concept of reducing complexity becomes even more relevant when working with newer process rich soil decomposition models.
I am currently investigating the effects of process-complexity on bulk carbon dynamics under heterogeneous parameterizations and look forward to extending this to inter-connected pore-structure.

# Project recaps
## Model driven data analysis
Soil temperature response is a major driver of shifts in soil carbon stocks in Earth system models.
This was the first project to see a direct change in soil organic carbon stocks in a set of field warmed experiments.
While Earth system models fell within this temperature response, they did not reflect the variability in the soil temperature response seen in the field.
Implying that models underestimate the uncertainty of the shift in soil carbon stocks over the 21st century.

- Todd-Brown K E O, Zheng B, Crowther T W. Field-warmed soil carbon changes imply high 21st century model uncertainty. Biogeosciences Discussion.  https://doi.org/10.5194/bg-2018-72. in open review.

## Post-hoc corrections to land carbon in Earth system model

Earth system models require a huge amount of personal and CPU time.
We used a reduced complexity framework to apply post-hoc corrections to the land carbon calculation of the CMIP5 Earth system models.
These corrections showed that nutrient (N and P) limitation on net primary productivity would likely reduce future land carbon inputs to such an extent that land carbon stocks may become a source of atmospheric carbon dioxide over the next century.
In addition, the soil carbon response is inline with experimental data but likely not reflective of real world uncertainty.

- Todd-Brown K E O, Zheng B, Crowther T W. Field-warmed soil carbon changes imply high 21st century model uncertainty. Biogeosciences Discussion.  https://doi.org/10.5194/bg-2018-72. in open review.
- Wieder, W, Cleveland, C, Smith, W, Todd-Brown, K. Future productivity and carbon storage limited by terrestrial nutrient availability. Nature Geoscience, https://doi.org/10.1038/ngeo2413. 2015.


## Drivers of soil dynamics in Earth system models

Soil carbon dynamics in Earth system models are primarily driven by differences in inputs (net primary production), soil temperature, and parameterization of intrinsic decay rates and the soil temperature sensitivity.
Model structural differences like the number of soil carbon pools and their connections, as well as other environmental sensitivities like moisture, did not drive model differences.
This effective structural homogeneity is surprising, but due to the fact that soil carbon stocks in most grid cells are close to steady state, and the basic mathematical structure of these models.

- Todd-Brown K E O, Zheng B, Crowther T W. Field-warmed soil carbon changes imply high 21st century model uncertainty. Biogeosciences Discussion.  https://doi.org/10.5194/bg-2018-72. in open review.
- Todd-Brown, K E O, Randerson, J T, Hopkins, F, Arora, V, Hajima, T, Jones, C, Shevliakova, E, Tjiputra, J, Volodin, E, Wu, T, Zhang, Q, and Allison, S D. Changes in soil organic carbon storage predicted by Earth system models during the 21st century. Biogeosciences, 11, 2341-2356, https://doi.org/10.5194/bg-11-2341-2014. 2014.
- Todd-Brown, K E O, Randerson, J T, Post, W M, Hoffman, F M, Tarnocai, C, Schuur, E A G, and Allison, S D: Causes of variation in soil carbon simulations from CMIP5 Earth system models and comparison with observations, Biogeosciences, 10, 1717–1736, https://doi.org/10.5194/bg-10-1717-2013. 2013.

## Benchmarking soils in Earth system models

In general, soil carbon models match global soil carbon stock estimates and then fall off in their performance at finer scales (biome and grid-by-grid comparison).
However, they do match experimental temperature response curves.

- Todd-Brown K E O, Zheng B, Crowther T W. Field-warmed soil carbon changes imply high 21st century model uncertainty. Biogeosciences Discussion.  https://doi.org/10.5194/bg-2018-72. in open review.
- Todd-Brown, K E O, Randerson, J T, Post, W M, Hoffman, F M, Tarnocai, C, Schuur, E A G, and Allison, S D: Causes of variation in soil carbon simulations from CMIP5 Earth system models and comparison with observations, Biogeosciences, 10, 1717–1736, https://doi.org/10.5194/bg-10-1717-2013. 2013.


# Publications

  1.  Todd-Brown K E O, Zheng B, Crowther T W. Field-warmed soil carbon changes imply high 21st century model uncertainty. Biogeosciences Discussion. https://doi.org/10.5194/bg-2018-72. in open review.
  2.  Bailey V, Bond-Lamberty B, DeAngelis K, Grandy A, Hawkes C, Heckman K, Lajtha K, Phillips R, Sulman B, Todd-Brown K, Wallenstein W. Soil carbon cycling proxies: Understanding their critical role in predicting climate change feedbacks. Global Change Biology.  https://doi.org/10.1111/gcb.13926. 2017
  3. Harden J W, Hugelius G, Ahlström A, Blankinship J C, Bond-Lamberty B, Lawrence C, Loisel J, Malhotra A, Jackson R B, Ogle S, Phillips C, Ryals R, Todd-Brown K, Vargas R, Vergara S E, Cotrufo M F, Keiluweit M, Heckman K A, Crow S E, Silver W L, DeLonge M, and Nave L. Pathways for the science community to characterize the state, vulnerabilities, and management opportunities of soil organic matter. Global Change Biology. doi: https://doi.org/10.1111/gcb.13896. 2017
  4. Luo Y, Shi Z, Lu C, Xia J, Liang J, Jiang J, Wang Y, KC M, Smith M J, Jiang L, Ahlström A, Chen B, Hararuk O, Hastings A, Hoffman F, Medlyn B, Niu S, Rasmussen M, Todd-Brown K, Wang Y-P. A theory on terrestrial carbon storage dynamics and its applications. Biogeosciences. doi: https://doi.org/10.5194/bg-14-145-2017. 2017.
  5. Crowther, T W, Todd-Brown, K E O, Rowe, C W, Wieder, W R, Carey, J C, Machmuller, M B, Snoek, L B, Fang, S, Zhou, G, Allison, S D, Blair, J M, Bridgham, S D, Burton, A J, Carrillo, Y, Clark, J S, Classen, A T, Dijkstra, F A, Elberling, B, Emmett, B, Estiarte, M, Frey, S D, Guo, J, Harte, J, Jiang, L, Johnson, B R, Kröel-Dulay, G, Larsen, K S, Laudon, H, Lavallee, J M, Luo, Y, Lupascu, M, Ma, L N, Marhan, S, Michelsen, A, Mohan, J, Niu, S, Pendall, E, Peñuelas, J, Pfeifer-Meister, L, Poll, C, Reinsch, S, Reynolds, L L, Schmidt, I K, Sistla, S, Sokol, N W, Templer, P H, Treseder, K K, Welker, J M, Reich, P, Bradford, M A. Quantifying global soil carbon losses in response to warming. Nature. doi: https://doi.org/10.1038/nature20150. 2016.
  6. Yan Z, Liu C, Todd-Brown K E, Liu, Y, Bond-Lamberty, B, Bailey, V L. Pore-scale investigation on the response of heterotrophic respiration to moisture conditions in heterogeneous soils. Biogeochemistry. doi:  https://doi.org/10.1007/s10533-016-0270-0. 2016.
  7. Phillips C L, Bond-Lamberty B, Desai A, Lavoie M, Risk D, Tang J, Todd-Brown K, Vargas R. Soil respiration measurements are under-utilized for interpreting and modeling terrestrial carbon cycling. Plant and Soil. doi: https://doi.org/10.1007/s11104-016-3084-x. 2016.
  8. Rasmussen, M, Hastings, A, Smith, M, Agusto, F, Chen-Charpentier B, Hoffman, F, Jiang, J, Todd-Brown, K, Wang, Y, Wang, Y P, Luo Y Q. Transit times and mean ages for nonautonomous and autonomous compartmental systems. Journal of Mathematical Biology. doi: https://doi.org/10.1007/s00285-016-0990-8. 2016.
  9. Wang, Y P, Jiang, J, Chen-Charpentier, Agusto, F B, Hastings, A, Hoffman, F, Rasmussen, M, Smith, M J, Todd-Brown, K, Wang, Y, Xu, X, Luo, Y Q. Responses of two nonlinear microbial models to warming and carbon input. Biogeosciences. doi: https://doi.org/10.5194/bg-13-887-2016. 2016.
  10. Luo, Y, Ahlström, A, Allison, S D, Batjes, N H, Brovkin, V, Carvalhais, N, Chappell, A, Ciais, P, Davidson, E A, Finzi, A, Georgiou, K, Guenet, B, Hararuk, O, Harden, J W, He, Y, Hopkins, F, Jiang, L, Koven, C, Jackson, R B, Jones, C D, Lara, M J, Liang, J, McGuire, A D, Parton, W, Peng, C, Randerson, J T, Salazar, A, Sierra, C A, Smith, M J, Tian, H, Todd-Brown, K E O, Torn, M, van Groenigen, K J, Wang, Y P, West, T O, Wei, Y, Wieder, W R, Xia, J, Xu, X, Xu, X and Zhou, T. Towards more realistic projections of soil carbon dynamics by Earth system models. Global Biogeochemical Cycles, doi: https://doi.org/10.1002/2015GB005239. 2015.
  11. Wieder, W, Allison, S, Davidson, E, Geogiou, K, Hararuk, O, He, Y, Hopkins, F, Luo, Y, Smith, M, Sulman, B, Todd-Brown, K, Wang, Y, Xia, J, Xu, X. Explicitly representing soil microbial processes in Earth system models. Global Biogeochemical Cycles, doi:https://doi.org/10.1002/2015GB005188. 2015.
  12. Goll, D S, Brovkin, V, Liski, J, Raddatz, T, Thum, T, Todd-Brown, K E O. Strong dependency of CO2 emissions from anthropogenic land cover change on soil parameterization and initial land cover. Global Biogeochemical Cycles, doi: https://doi.org/10.1002/2014GB004988. 2015.
  13. Wieder, W, Cleveland, C, Smith, W, Todd-Brown, K. Future productivity and carbon storage limited by terrestrial nutrient availability. Nature Geoscience, doi:https://doi.org/10.1038/ngeo2413. 2015.
    * Wieder, W, Cleveland, C, Smith, W, and Todd-Brown, K: Reply to “Land unlikely to become large carbon source,” Nature Geoscience, doi:https://doi.org/10.1038/ngeo2606. 2015.
  14. Todd-Brown, K E O, Randerson, J T, Hopkins, F, Arora, V, Hajima, T, Jones, C, Shevliakova, E, Tjiputra, J, Volodin, E, Wu, T, Zhang, Q, and Allison, S D. Changes in soil organic carbon storage predicted by Earth system models during the 21st century. Biogeosciences, 11, 2341-2356, doi:https://doi.org/10.5194/bg-11-2341-2014, 2014.
  15. Todd-Brown, K E O, Randerson, J T, Post, W M, Hoffman, F M, Tarnocai, C, Schuur, E A G, and Allison, S D: Causes of variation in soil carbon simulations from CMIP5 Earth system models and comparison with observations, Biogeosciences, 10, 1717–1736, doi:https://doi.org/10.5194/bg-10-1717-2013, 2013.
  16. Todd-Brown, K E O, Hopkins, F M, Kivlin, S N, Talbot, J M, and Allison, S D: A framework for representing microbial decomposition in coupled climate models, Biogeochemistry, 109, 19–33, doi:https://doi.org/10.1007/s10533-011-9635-6, 2012.
  17. Sklar, P, Smoller, J W, Fan, J, Ferreira, M A R, Perlis, R H, Chambert, K, Nimgaonkar, V L, McQueen, M B, Faraone, S V, Kirby, A, de Bakker, P I W,  Ogdie, M, Thase, M, Sachs, G, Todd-Brown, K, Gabriel, S, Sougnez, C, Gates, C, Blumenstiel, B, Defelice, M, Ardlie, K, Franklin, J, Muir, W, McGhee, K, Macintyre, D, McLean, A, Vanbeck, M, McQuillin, A, Bass, N, Robinson, M, Lawrence, J, Anjorin, A, Curtis, D, Scolnick, E, Daly, M, Blackwood, D, Gurling, and H, Purcell, S: Whole-genome association study of bipolar disorder, Molecular Psychiatry, 13(6), 558–569, doi:https://doi.org/10.1038/sj.mp.4002151, 2008.
  18. Purcell, S, Neale, B, Todd-Brown, K, Thomas, L, Ferreira, M A R, Bender, D, Maller, J, Sklar, P, de Bakker, P I W, Daly, M J, and Sham, P C: PLINK: A Tool Set for Whole-Genome Association and Population-Based Linkage Analyses, American Journal of Human Genetics, 81(3), 559–575, doi:https://doi.org/10.1086/519795, 2007.

# Contact me

https://github.com/ktoddbrown

https://twitter.com/KatheMathBio

https://scholar.google.com/citations?user=4qJdWTsAAAAJ

ktoddbrown at@at gmail .dot. com <- I don’t know if there is someway to keep this from getting scrapped but let’s try?

# Resources

## How to
Software and Data Carpentry, https://software-carpentry.org/ http://www.datacarpentry.org/ Workshops for data/software skills targeting scientific researchers.

The Carpentries Handbook, https://docs.carpentries.org/ Information on developing, training, and delivering workshops on data/software skills to the science community.

The Open Science Training Handbook, https://legacy.gitbook.com/book/open-science-training-handbook/book/details A living book on what open science is and how to do open science.

## Repositories and archives

Environmental Data Initiative, https://environmentaldatainitiative.org/ Support, training, and resources to help archive as well as publish data and metadata. NSF funded.

Environmental Systems Science Data Infrastructure for a Virtual Ecosystem (ESS-DIVE) http://ess-dive.lbl.gov/ Environmental data repository for DOE funded projects from SBR and TES programs.

Coupled model intercomparison project phase 5 (CMIP5) https://cmip.llnl.gov/cmip5/ Earth system model simulation outputs that informed the last IPCC report.
