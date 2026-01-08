# LabNotebook
Gignoux-Wolfsohn Lab at University of Massachusetts Lowell https://gwlab.org/
Started Sep 2023

## Table of Contents
### Protocols
- Contains: Dna extractions, microbiome enrichments, qubit
  
### 09-23-CBC_Enrichments
- enrichments done on CBC samples for 10/23 sequencing
- more info on - https://github.com/sagw/SCTLD_samples/blob/main/Sample_Data/Metagenomics_Tracker_Belize.csv
  
### 2019_2022_resequencing
- dna extractions, enrichments, and DNA concentrations on all 2019 and 2022 samples covering species MCAV, PSTR, OFAV, and OANN (some will be resequenced, some will be sequenced for the first time). more info on the inventory notebook and resequence_combined spreadsheet

#### Scripts 
- Extraction_Locat_Update: updates cbc_samples with extraction locations from metagenomics tracker
- resequence_plan: Determine number of samples to extract and enrich (2019 and 2022 only)
- SummaryStats: summarize number of samples for each species and categorize by year and health status
- Merge_reseq_meta: add final info from Resequence_combined.csv to metagenomics tracker 

### genohub
- Genohub submission sheets (forms for metagenomic sequencing sent to genohub sequencer)

### Misc2024
- miscellaneous lab tasks (pipette testing)

### Nutrients
- lab notebook for nutrient analyses 

#### mbl_nuts112025
- final nutrient processing (n03,nh4,po4,chla) was done at MBL in 11/2025
- contains raw results and final concentrations 
##### protocols 
- lab protocols used for post-collection processing done at MBL 
- contains protocols for ammonia, no3 and po4 (lachat), and chla 
##### raw
- raw results for ammonia, no3, po4, and chla 
##### metadata 
- metadata for input sample data 
- original sample inventory in [GW lab drive](https://drive.google.com/drive/u/0/folders/19viB0CbY0K2-OwIIyQ1d6vyVJVkN8GNA)
##### scripts_processing
- R notebooks for processing sample data, computing final concentrations, and visualizing data 
- input is from raw data and metadata in this mbl_nuts112025 folder

#### DO
- Dissolved Oxygen (DO) HOBO Logger data 

#### nitrate_2024
- protocol development and testing for nitrate using colorimetric well plates 
- this can largely be ignored since the final protocol used was the lachat at MBL (in mbl_nuts112025 folder)