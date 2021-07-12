# Source_analysis
There are two main notebooks and two supplementary notebooks. 

## SummaryEnergyConsumption.ipnynb
This is the updated main notebook applied to retrieve Energy Consumption and Generation of the site. 
This Notebook can be altered to apply to different sites.

## Source-analysis.ipynb
This main notebook retrieves both Energy logs and Trend Logs and merges into a single DataFrame.
This notebook is limited to analyse 12 meters for a single run through the entire notebook, due to the ratelimit and large dataset it will produce. 

## ActiveEnergy_Consumption(2).ipynb
This notebook only retrieves the EnergyLog for Active Energy Consumption(kWh) for all physical meters excluding Meter 17600. 

## Active-Energy-Consumption - Meter 17600.ipynb
This notebook has the same commands as ActiveEnergy_Consumption(2).ipynb, however only analyses Meter 17600(calculated Meter). 
