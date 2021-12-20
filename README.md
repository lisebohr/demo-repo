# EM_Case
This repository contains 8 files


## Description of contents

Two input files 
- **ActualGenerationperProduction.csv** Hourly generation by production type retrieved from ENTSO-e
- **CO2eq_mapped.csv** CO2 equivalent by production type from ElectricityMap's public github repository. This file has been mapped manually to make production type match data from ENTSO-e 

Two jupyter notebooks: 
- **00_ReadCleanUpload** Read, clean and upload the two files SQLite Database above
- **01_Join&Calc** Intention was to join, aggregate, and calculate proportion mix and carbon intensity. I had an issue with the join, so I completed the in Alteryx. 

Output 
- **lteryxJoin&Calc.csv** Output from Alteryx including Proportion and carbon intensity measures

Visuals
- **Visualisations for slides__6654.twbr** Tableau Workbook containing the visuals presented in slidedeck 
