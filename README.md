# EXTRACT CONTENT FROM UNSTRUCTURED TYPE CERTIFICATE DATA SHEET
## This Project is sponsored by the FAA and the Data Analytics Department of GMU
### Team Aviators

#### Abtract
A Type Certificate Data Sheet (TCDS) is a document that consists of information about a flight model, where the data acts as a standard for flight manufacturers. Every aircraft manufactured by any organization must adhere to all the requirements set by the government and will need a TCDS issued by the Federal Aviation Administration (FAA) to fly in the USA. This study aims to extract the prioritized information for each model from the TCDS. The FAA has a dynamic dataset, and each TCDS is populated whenever a new model gets added. Formats have evolved over decades, starting from the early 1920s. Therefore, we have numerous variations in the TCDS formats. Extracting critical information into an easily accessible datasheet is vital to save time and effort for the end user of the TCDS. The TCDS has been used and modified for a long time, however, automating and extracting prioritized data remains to be accomplished. Our task was to determine what methods could reach that goal and produce a format conducive to getting the required information. The dataset is given by the FAA, which consists of more than 2000 pdf files; we have performed our pre-processing, data analysis, and cleaning to extract high-priority information. Using the geometry of the TCDS, its structure, and with the support of existing Python libraries, we can differentiate between key terms, model header, and information. The result is a two-column format output file as a data frame and CSV file containing all the prioritized information for each model in the TCDS. They are reader-friendly and make it easy to pull up desired information. The result consists of a python code, producing an output of structured format with over 75% coverage of the critical information.

### Requirements Environment
Most of us using Conda Environment, but the requirements.txt is updated on the repo.

### Overviews of the repo
Folder dataset_tcds contains all the tcds we was working on, and folder csv contains the products after processing. 

### Members of the team 
Bach Xuan Le: github.com/Bbteela\
Kai Chun Chan: github.com/KaiChan20\
Patcharaporn Adchariyavivit: github.com/PatchaAdcha\
Rohit Varma Chekuri: github.com/rohitcrft79\
Saroj Siril Palaparthi: github.com/Sarojsiril1\
