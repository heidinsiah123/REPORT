# The Influence of Diabatic Heating on North Pacific Climate Variability

Contents
 - [x] Introduction
 - [x] Data
 - [x] Code Description
 - [x] Result 
   - [ ]  Diabatic heating anomalies over levels at different times
   - [ ]  Correlation between Nino 3.4 and the North Pacific
   - [ ]  Applying EOFs to diabatic heating.
   - [ ]  Linear Regression between heating and Nino3.4
   - [ ]  Applying EOFs on the regressed data to determine any spatial variabiltiy.
 - [x] Summary 


# Introduction

Diabatic heating is the process of heat exchange between a system and its environment, leading to temperature changes. Unlike adiabatic processes, it involves the addition or removal of heat. This concept is essential in atmospheric sciences for understanding weather and climate.
The primary source of diabatic heating is the absorption of solar radiation, which warms the Earth's surface and lower atmosphere, influencing weather patterns and temperature gradients. Other major sources are radiational processes, advection, latent and sensible heat flux.
Understanding the role of diabatic heating in climate variability is crucial because it directly influences the amount of heat that drives atmospheric and oceanic processes, which, in turn, govern the variability of climate systems. In climate variability, diabatic heating acts as a key driver by creating energy imbalances that influence large-scale circulation systems. For instance, in the tropics, intense diabatic heating due to solar radiation and latent heat release fuels convective systems like the Hadley Cell, which impacts global weather patterns. Similarly, during El Niño and La Niña events in the Pacific, diabatic heating in the Nino3.4 region alters atmospheric circulation, leading to changes in precipitation, storm tracks, and temperature anomalies across the globe.
The amount of diabatic heating also determines the strength and intensity of weather systems. For example, in tropical cyclones, the release of latent heat during condensation powers the system, influencing its intensity and movement. Similarly, sensible heat fluxes from land-sea temperature differences and radiational cooling or heating contribute to regional climate variability, such as the formation of monsoons or mid-latitude storm systems. By understanding how diabatic heating distributes heat and drives energy exchanges, scientists can better predict and model climate variability. This knowledge helps in assessing the impacts of phenomena like droughts, floods, heatwaves, and changing storm patterns, which are influenced by variations in diabatic heating. As climate change continues to alter the intensity and frequency of diabatic heating processes, understanding their role becomes even more critical for predicting future climate scenarios and their potential impacts on ecosystems and human systems.

# Data 
 - [x] Data types
  - [ ] Diabatic heating from global reanalysis products such as ERA5 (ECMWF Reanalysis)
    - [ ] Temporal Resolution : 6 hourly data
    - [ ] Spatial Resolution : Globe, but restricted to the North Pacific in this work (23.5°N–70°N, 120°E–120°W)
    - [ ] Temporal Coverage : 1982 - 2017
    - [ ] Format: NetCDF (Network Common Data Form) format
  - [ ] Sea Surface Temperature from Optimum Interpolation Sea Surface Temperature (OISSTV2 High Resolution Dataset)
    - [ ] Temporal Resolution : Daily data
    - [ ] Spatial Resolution : Globe, but restricted to the North Pacific in this work (23.5°N–70°N, 120°E–120°W)
    - [ ] Temporal Coverage : 1982 - 2017
    - [ ] Format: NetCDF (Network Common Data Form) format


# Results
 ## Estimating diabatic heating anomalies over levels at different times
 ### Heating Anomalies at different levels on 1982

   ![download-19](https://github.com/user-attachments/assets/a918a7ab-df31-4a64-a0ed-ad2239d50fca)
   
   
  ## Heating Anomalies at different levels on 1983
   ![download-21](https://github.com/user-attachments/assets/f8f5ea16-acb1-44cc-9485-a0fe09366763)
 

   #### Heating Anomalies at different levels on 2017
   ![download-19](https://github.com/user-attachments/assets/510fe7b4-3e96-491d-aba2-398d1888d0df)


   ### Heating Anomalies over Tropical Pacific on 1982 and 1983
   ![download-22](https://github.com/user-attachments/assets/695ddfb7-cc81-49c7-a694-2c3a11d3508d)
   
   ![download-23](https://github.com/user-attachments/assets/1b61961b-0e34-49cb-98f3-cc47491ee697)


 ## Estimating the Correlation between Nino 3.4 and the North Pacific

   ![download-10](https://github.com/user-attachments/assets/23977a3e-d050-40fe-8a8f-68cf1b7c1047)


   ![download-11](https://github.com/user-attachments/assets/c3690bc4-d995-4d22-983e-3149eaaa498c)


  ## Determining possible spatial patterns over North Pacific when EOFs are applied to diabatic heating. 
   ### Including the tropics (0 - 23.5N )

   ![download-14](https://github.com/user-attachments/assets/ee3b38bf-62fc-4003-a6d6-f80182c6d252)
     
     
   ![download-13](https://github.com/user-attachments/assets/3e2cf82b-c168-443b-a660-82ef89ea9f96)

   ###  Including the tropics (0 - 23.5N )

          
   ![download-15](https://github.com/user-attachments/assets/662baba1-563e-41bf-9bdd-fcb3d1bdccb7)


   ![download-16](https://github.com/user-attachments/assets/58772c4e-f9b7-4678-9785-8e728e5e5b72)

## Linear Regression between heating and Nino3.4

   ![download-17](https://github.com/user-attachments/assets/089b3847-2f01-4867-8393-9622f239bd83)
     
   ![download-18](https://github.com/user-attachments/assets/c49c6406-3c9b-478f-b650-600fedec0a25)
 
# Summmary

Correlation Between Diabatic Heating and Niño3.4:

The analysis reveals a strong relationship between diabatic heating and Niño3.4 index, suggesting that diabatic heating patterns are significantly modulated by El Niño-Southern Oscillation (ENSO) events.
During El Niño events, enhanced diabatic heating is observed in the central and eastern equatorial Pacific, aligning with warm sea surface temperature anomalies.
Conversely, during La Niña events, diabatic heating shifts westward, consistent with cooler SST anomalies in the Niño3.4 region.

Spatial Patterns (EOF Analysis):

The leading EOFs of diabatic heating depict dominant spatial patterns that align with the characteristic phases of ENSO. These spatial modes emphasize the importance of tropical Pacific dynamics in shaping global atmospheric circulation.
The first EOF likely captures the canonical ENSO signal, with diabatic heating anomalies centered over the Niño3.4 region, while higher EOFs might represent secondary modes or regional influences.
Temporal Variability:

The principal components (PCs) corresponding to the EOFs show that the temporal variability of diabatic heating is highly correlated with the Niño3.4 index, further confirming ENSO's dominant influence.
Implications for Climate and Weather:

Diabatic heating anomalies induced by ENSO events can significantly alter the atmospheric circulation, including the Walker and Hadley cells, thereby impacting global climate patterns such as monsoons, mid-latitude storms, and even polar weather systems.
These findings underscore the role of diabatic heating as a key mechanism in the atmospheric response to SST anomalies in the Niño3.4 region.
























