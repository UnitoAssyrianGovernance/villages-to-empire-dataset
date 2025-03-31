This readme file was generated on 2025-03-31 by A. Titolo, adapted from the template provided by the [Cornell Data Services](https://data.research.cornell.edu/data-management/sharing/readme/)

## GENERAL INFORMATION

**Title of Dataset**: From Villages to Empires: Archaeological Settlements of the South Levant from the Chalcolithic to the Byzantine Period

**Author/Data Curator and Management Information**  
Name: Andrea Titolo  
ORCID: [0000-0002-7322-8634](https://orcid.org/0000-0002-7322-8634)  
Institution: University of Turin, Department of Historical Studies  
Address: Via Sant'Ottavio 20 10124 Torino, Italy 
Email: andrea.titolo@unito.it  


**Author/Principal Investigator Information**  
Name: Alessio Palmisano  
ORCID: [0000-0003-0758-5032](https://orcid.org/0000-0003-0758-5032)  
Institution: University of Turin, Department of Historical Studies  
Address: Via Sant'Ottavio 20 10124 Torino, Italy  
Email: alessio.palmisano@unito.it   

**Date of data collection**: 2023-02-01 to 2025-01-31 

**Geographic location of data collection**:

Palestine and the central regions of Israel:

- Northern boundary: 32.57228471 (decimal degrees).
- Southern boundary: 31.13314649
- Eastern boundary: 35.57204756
- Western boundary: 34.47523021

**Information about funding sources that supported the collection of the data**: 

Fundings were provided by the Gerda Henkel Stiftung for the project “Governance Policies and Political Landscapes in the Southern Levant under the Neo-Assyrian Empire” (grant number: AZ 31/F/21, PI Alessio Palmisano).

## SHARING/ACCESS INFORMATION

**Licenses/restrictions placed on the data**: [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)

**Links to publications that cite or use the data**: TBA

**Links to other publicly accessible locations of the dat**a: TBA

**Data Origin**: Secondary and Processed data from originally published materials.

**Sources**: 

- Bar, S and Zertal, A 2022 The Manasseh Hill Country Survey Volume 7: The South-Eastern Samaria Shoulder, from Wadi Rashash to Wadi ’Aujah. Leiden: Brill. Accessed: Feb. 12, 2023. [Online]. Available: https://brill.com/display/title/62098.
- Bar, S and Zertal, A 2021 The Manasseh Hill Country Survey Volume 6: The Eastern Samaria Shoulder, from Nahal Tirzah (Wadi Far’ah) to Ma’ale Ephraim Junction. Leiden: Brill. Accessed: Feb. 12, 2023. [Online]. Available: https://brill.com/display/title/60190.
- Finkelstein, I, Lederman, Z and Bunimovitz, S 1997 Highlands of many cultures: The Southern Samaria survey ; the sites, 1. Tel Aviv: Institute of Archaeology of Tel-Aviv University, Publications Section. Available: https://cris.tau.ac.il/en/publications/highlands-of-many-cultures-the-southern-samaria-survey-the-sites.
- Greenberg, R and Keinan, A 2009 Israeli Archaeological Activity in the West Bank 1967-2007: A Sourcebook. Jerusalem: Ostracon. Available: https://www.emekshaveh.org/he/wp-content/uploads/2013/09/WBADB_sourcebook.pdf.
- Pedersén, O 2012 Ancient Near East on Google Earth: Problems, Preliminary Results, and Prospects, in Proceedings of the 7th International Congress on the Archaeology of the Ancient Near East: 12 April - 16 April 2010, the British Museum and UCL, London. 3, Fieldworks and recent research, R. Matthews and J. Curtis, Eds., Wiesbaden: Harrassowitz, 385–393.
- Zertal, A 2004 The Manasseh Hill Country Survey, Volume 1: The Shechem Syncline. Leiden: Brill. Available: https://brill.com/display/title/11056.
- Zertal, A 2007 The Manasseh Hill Country Survey, Volume 2: The Eastern Valleys and the Fringes of the Desert. Leiden: Brill. Available: https://brill.com/display/title/13258.
- Zertal, A and Mirkam, N 2016 The Manasseh Hill Country Survey: Volume 3: From Nahal Iron to Nahal Shechem. Leiden: Brill. Available: https://brill.com/edcollbook/title/31740.
- Zertal, A and Bar, S 2017 The Manasseh Hill Country Survey Volume 4: From Nahal Bezeq to the Sartaba. Leiden: Brill. Accessed: Feb. 12, 2023. [Online]. Available: https://brill.com/display/title/34196.
- Zertal, A and Bar, S 2019 The Manasseh Hill Country Survey Volume 5: The Middle Jordan Valley, from Wadi Fasael to Wadi ‘Aujah. Leiden: Brill. Accessed: Feb. 12, 2023. [Online]. Available: https://brill.com/display/title/54817.

**Recommended citation for this dataset**: 

TBA

## DATA & FILE OVERVIEW

**Files List**:

- **dataset** folder:
  - **dataset** - a geopackage database containing two layers:
    - **archaeo_surveys_area** – a polygon layer representing the spatial extent of the archaeological surveys from which settlements data have been collected.
    - **archaeo_sites** – a point layer of archaeological sites in South Levant.
  - **archaeo_sites** - a set of two files respectively providing a spreadsheet (.csv) of sites in South Levant, and a field description for the attributes table of the sites (.txt).


**Relationship between files**: 

- archeo_sites.txt contains coded information about the attributes of the sites in the geopackage database. In particular, information on Location Quality and Size quality key codes.


## METHODOLOGICAL INFORMATION

**Description of methods used for collection/generation of data**: **TBA**
<!-- <include links or references to publications or other documentation containing experimental design or protocols used in data collection> -->

**Methods for processing the data**:

- Digitalization of archaeological surveys and sites from published materials.
- Chronological harmonization of the source data.
- In QGIS: standardisation of data in a geopackage database with each site phase represented by a point geometry.
- Additional quantitative and qualitative information added to the database.

**Instrument- or software-specific information needed to interpret the data**: 

- A GIS software is necessary to visualize the geopackage database. [QGIS](https://qgis.org) is a recommended free, open-source, and multi-platform software for this purpose. Data was generated using QGIS 3.28 and higher. Some vizualisation feature may not work properly with older versions of QGIS.

Standards and calibration information, if appropriate: 

Chronological Scheme for South Levant used in the dataset (see the paper for more information)

| Period                          | Absolute Dates | BP Dates            |
|---------------------------------|----------------|---------------------|
| Chalcolithic                     | 4500-3800 BC   | 6450-5750/5550      |
| Early Bronze Age IA             | 3800-3300 BC   | 5750/5550-5250      |
| Early Bronze Age IB             | 3300-3050 BC   | 5250-5000/4950      |
| Early Bronze Age II             | 3050-2850 BC   | 5000/4950-4800/4750 |
| Early Bronze Age III            | 2850-2500 BC   | 4800/4750-4450      |
| Early Bronze Age IV/Int. Bronze | 2500-2000 BC   | 4450-3950/3900      |
| Middle Bronze Age I             | 2000-1750 BC   | 3950/3900-3700      |
| Middle Bronze Age II-III        | 1750-1550 BC   | 3700-3500           |
| Late Bronze Age I               | 1550-1400 BC   | 3500-3350           |
| Late Bronze Age II              | 1400-1200 BC   | 3350-3150           |
| Late Bronze Age III             | 1200-1150 BC   | 3150-3100           |
| Iron Age I                      | 1150-980 BC    | 3100-2930           |
| Iron Age IIa                    | 980-830 BC     | 2930-2780           |
| Iron Age IIb                    | 830-720 BC     | 2780-2670           |
| Iron Age IIc                    | 720-539 BC     | 2670-2489           |
| Iron Age III (Persian)          | 539-333 BC     | 2489-2283           |
| Hellenistic                     | 333-63 BC      | 2283-2013           |
| Early Roman                     | 63 BC -70 AD   | 2013-1880           |
| Late Roman                      | 70-324 AD      | 1880-1626           |
| Byzantine                       | 324-638 AD     | 1626-1312           |

**Quality-assurance procedures performed on the data**: 

- All data have been checked and standardised.
- Site extent have been refined by using multiple sources wherever possible (archaeological survey and excavation reports)
- Site location have been cross-checked with multiple sources and refined by using satellite imagery, topographic maps, and other published materials.

**People involved with sample collection, processing, analysis and/or submission**: 

- Andrea Titolo
- Alessio Palmisano


## DATA-SPECIFIC INFORMATION FOR: dataset.gpkg - archaeo_sites / archaeo_sites.csv
<repeat this section for each dataset, folder or file, as appropriate>

**Number of Fields**: 27

**Number of rows**: 5542 

**Fields List and Description:**

- SiteID (character): project unique site ID to identify the site
- Name (character): name of the site as reported from the original source
- NameAlt (character): alternative name of the site provided by the original or other sources
- AncientName (character): if applicable, name(s) for wich the site was known in antiquityu
- Type (character): typology of site (e.g. settlement, cave, etc.)
- Subtype (character): archaeological features present on the site
- Morphology (character): morphology of the site (e.g. Tell, Flat site)
- Period (character): cultural period of the site-phase
- StartDate (character): starting date of the site-phase
- EndDate (character): ending date of the site-phase
- ArchaeoStatus (character): if the archaeological site was excavated/surveyed/sampled
- Notes (character): any useful notes about the site archaeology
- Latitude (numeric): WGS84 latitude in decimal degrees
- Longitude (numeric): WGS84 longitude in decimal degrees
- Northing (numeric): UTM36N northings
- Easting (numeric): UTM36N eastings
- LocQual (character): location accuracy of the point representing the site
- SizeHa (numeric): size of the site in hectares
- SizeQual (character): quality of the dimensional information
- Source (character): main bibliographic reference
- Pages (character): page from the main bibliographic reference. If an online database, this is a url
- SourceID (character): site ID from the main bibliographic reference
- AltSource (character): alternative bibliographic reference (in case of visit from different surveys)
- AltSourcePages (character): pages or url for the alternative bibliographic reference
- AltSourceID (character): Site ID for the alternative bibliographic reference
- AltSizeHa (numeric): alternative site size (if applicable) in the alternative bibliographic reference
- AltSizeQual (character): quality of the alternative dimensional information