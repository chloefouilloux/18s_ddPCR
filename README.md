# 18s_ddPCR

.readme

Last updated: 11 JAN 2025 BY CHLOE A. FOUILLOUX

18S DDPCR: Creation of ddPCR primers to detect both Cyclopoid copepods and S. solidus helminths. Generation of standards, quantification of infection rates in natural samples.

#Code Files

Main text code is:
 > MolEco_ddPCR_Paper2024.Rmd

Supplementary Codes testing primer/probe-primer specificity on related spcies is 
  > Supp_Code_ProbePrimer.Rmd


# Key Variables

| Variable Name     | Units         | Notes                                                                                  |
|--------------------|---------------|----------------------------------------------------------------------------------------|
| Dilution          | Categorical   | Dilution factor from 10ng/uL                                                           |
| Concentration     | copies/uL     | Concentration of 18S rRNA gene from QuantaSoftware                                     |
| AcceptedDroplets  | Integer       | Number of droplets in ddPCR provided fluorescent data (QC). Should be >10000.         |
| Treatment         | Factor        | Can be either multiplexed or singleplexed. Refers to the primers added to mastermix.  |
| Ch1 Amplitude     | Number        | This is the amplitude of droplets for *S. solidus*.                                   |
| Ch2 Amplitude     | Number        | This is the amplitude of droplets for Cyclopoid copepods.                             |
| Species           | Factor        | Either Copepod or *Schistocephalus*                                                   |
| Target            | Factor        | Fluorescent dye used for each species. FAM == Schisto, HEX == Copes                   |



# Data Files

## MoleculEcology_ddPCRfullrun
This is the raw data file generated by QuantaSoft ddPCR machine.

## Infected_10_2
This is a single replicate 10-2 dilution from the 100 infected copepod standards. This is well-specific information for details on every single droplet that was amplified. 

## Infected_10_3
This is a single replicate 10-3 dilution from the 100 infected copepod standards. This is well-specific information for details on every single droplet that was amplified. 

## Infected_10_4
This is a single replicate 10-4 dilution from the 100 infected copepod standards. This is well-specific information for details on every single droplet that was amplified. 

## Infected_10_5
This is a single replicate 10-5 dilution from the 100 infected copepod standards. This is well-specific information for details on every single droplet that was amplified. 

## Infected_10_6
This is a single replicate 10-6 dilution from the 100 infected copepod standards. This is well-specific information for details on every single droplet that was amplified. 

## ZOOP_BLACKLAKE_10_2
This is field data from a zooplankton tow from Blackwater Lake, Vancouver Island. This is a single replicate 10-2 dilution. This is well-specific information for details on every single droplet that was amplified

## ZOOP_PACHENALAKE_10_2
This is field data from a zooplankton tow from Pachena Lake, Vancouver Island. This is a single replicate 10-2 dilution. This is well-specific information for details on every single droplet that was amplified

## WATER_BLACKWATERLAKE
This is field data from a filtered water from Blackwater Lake, Vancouver Island. This is a single undiluted replicate. This is well-specific information for details on every single droplet that was amplified.


# Supplementary Data Files

## SupplementaryMaterials_ddPCR_2025
This is the raw data file generated by QuantaSoft ddPCR machine.

## Calanoid/Cotti_Example
This is a single replicate 10-3 dilution either calanoid or cyclopoid copepod standards. This is well-specific information for details on every single droplet that was amplified. 

## Solidus/Pungitii/Cotti_Example
This is a single replicate 10-3 dilution either Schistocelphalus solidus/cotti/pungitii standards. This is well-specific information for details on every single droplet that was amplified. 

<img width="1402" alt="Fig1_Annotated" src="https://github.com/user-attachments/assets/c4d47f4e-6f52-4e5b-8b3b-006e61302eac" />


