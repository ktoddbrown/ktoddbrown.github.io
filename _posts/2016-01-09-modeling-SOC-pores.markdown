---
layout: post
title:  CIPS model (Kuka et al, 2007)
comments: True
date: 2016-01-09
tags: [lit-review, SOC-model]
---

Soil carbon decomposition is typically modeled as a first order linear decay. Soil carbon is divided between N pools and leaves those pools at a rate that’s proportional to the amount of carbon in those pools; some of that carbon is respired as $$CO_2$$ the rest is transferred to other pools. Early models framed the creation of these different pools as a function of their chemical structure (sugars decompose faster then wood for example). However it’s become clear in more recent research that other physical processes also influence carbon stabilization. 

The model proposed by [Kuka et al, 2007](http://linkinghub.elsevier.com/retrieve/pii/S0304380007003080) combines this traditional first order linear decay approach with an additional pore size layer. Pore space is broken up into three bins connected via a single disolved organic matter pool. Each pore bin contains four decomposition pools with a partial feedback structure. $$CO_2$$ is only respired in the transfer into the biomass pool but the size of the biomass pool does not effect the size of that carbon flux directly. Different pore bins are active under different moisture conditions. In theory, the sizes of these pore bins, and biomass pool are all measurable, and many of the proposed coefficients can be well constrained.

As a first order linear model this follows the traditional basic structure:

$$\frac{dC}{dt}=u-AKC$$

where C is an array representing the carbon stock of different pools, $$k$$ the decomposition matrix, and $$u$$ the carbon inputs. Such that the carbon pools are initial split into the three pore bins (1-micro, 2-meso, 3, macro) plus the dissolved organic matter pool (DOM), and then further divided into labile fresh organic matter (L), recalcitrant fresh organic matter (R), active organic matter (aka biomass) (AOM), and then finally refractory organic matter (ROM).

$$C=(C_{L1}, C_{R1}, C_{ROM1}, C_{AOM1}, 
	 C_{L2}, C_{R2}, C_{ROM2}, C_{AOM2},
	 C_{L3}, C_{R3}, C_{ROM3}, C_{AOM3},
	 C_{DOM})’$$

$$K=diag(k_{L1}, k_{R1}, k_{ROM1}, k_{AOM1}, 
	 k_{L2}, k_{R2}, k_{ROM2}, k_{AOM2},
	 k_{L3}, k_{R3}, k_{ROM3}, k_{AOM3},
	 k_{DOM})$$

$$A_{i} =\pmatrix{-1&\cdot&\cdot&\cdot \cr
		 \cdot&-1&\cdot&\cdot \cr
		 \cdot&\cdot&-1&\alpha_{AOMi} \cr
		 \eta_{Li} & \eta_{Ri} & \eta_{ROMi} & -1
}$$; 
$$a_i = \pmatrix{\cdot \cr \cdot \cr 1-\alpha_{AOMi} \cr \eta_{DOM}}$$;
$$A = \pmatrix{A_1 & \ldots & \ldots & a_1 \cr
	       \ldots & A_2 & \ldots & a_2 \cr
		\ldots & \ldots & A_3 & a_3 \cr
		\ldots & \ldots & \ldots & -1 \cr
 }$$

In other words carbon is transferred from the fresh organic matter pools to the active organic matter, and cycled between the AOM-ROM and AOM-DOM pools. Inputs come into the fresh organic matter pools and DOC pool. Thus this model is a partial feedback pool. But the super model of the different pore bins are almost parallel if it was not for the DOM pool which links all three pore bins. 

I’m a little skeptical that this model is as measurable as is claimed in the manuscript but it is an interesting combination of a first order decay model combined explicit pore size distribution. I suspect that the mathematics may simplify due to the extreme similarity in the pore sub-models; the decomposition rates are sensitive to the different oxygen levels in each pore space and unique moisture properties however this could be as effectively represented via a new sensitivity function in the base submodel.
