#README

IYS_Standardized_Zoop_Taxa_Abundance_2022.csv

This dataset contains zooplankton abundances from bongo tows collected during International Year of the Salmon (IYS) Expeditions in 2022 aboard the CCGS John Franklin, the NOAA Bell M. Shimada, the R/V Tinro, and the NW Explorer. The purpose of this dataset was to standardize zooplankton taxonomy in such a way as to allow comparison of zooplankton community composition and abundances across the 2022 International Year of the Salmon (IYS) Expedition while retaining as much taxonomic resolution as possible. Multiple taxonomists were responsible for sample processing and their original identifications are retained in the column ‘original_id’.  The standardization for 2022 differs from the standardization for 2019-2022 with respect to the treatment of the following genera: Calanus, Neocalanus, Paracalanus, Pseudoamallothrix, Scolecithricella, Spinocalanus, and Phronima. 


Expedition: Year of expedition preceded by ‘IYS’

Vessel: Shortname of vessel from which sample was collected

Station: Original station naming has been retained with a vessel-specific prefix added to ensure unique station names. F = CCGS Sir John Franklin, K = R/V Professor Kaganovskiy, L = Pacific Legacy, N = F/V Northwest Explorer, S = NOAA Bell. M. Shimada, T = R/V Tinro 

TaxGroup: Broad taxonomic category

Taxon: Standardized taxonomic assignment. May include stage information where assignment is split by development stage (e.g. Metridia pacifica C5-C6, Metridia spp. C1-C4).

original_id: original taxonomic assignment

Dev_Stage: Developmental stage, where recorded. C1, C2, etc., refer to copepodid stage 1, copepodid stage 2, etc. In the case of siphonophores, this may refer to the part of the siphonophore counted, rather than a stage of development.

Sex: Sex, where recorded

Length: As recorded by taxonomist. 

Abundance_m3: Abundance in individuals per cubic metre. Note that Franklin samples were collected over the top 300 m of the water column, whereas other vessels collected over the top 250 m.

Abundance_m2: Abundance in individuals per square metre, calculated as Abundance_m3*300 for Franklin samples and Abundance_m3*250 for all remaining samples.

eventID: IYS unique event identifier 




