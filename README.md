
Please cite this data as the following: 

Relative DOI: https://doi.org/10.64898/2026.10.02.756347

Associated GitHub Repository: https://github.com/davidliu-lab/mucosal_melanoma_atlas_manuscript_code_2026

# Data Access Information
------------------ 
TABLE OF CONTENTS
------------------
​
* GENERAL INFORMATION
  * ASSOCIATED PUBLICATION
  * RECOMMENDED CITATION
  * USEFUL LINKS
* ACCESS THE DATASET
  * FILE ORGANIZATION
  * REPOSITORY LINKS
  * FILE LIST
* ADDITIONAL NOTES/COMMENTS
​
--------------------
GENERAL INFORMATION
--------------------
​
1. **Genomic classification and immune profiling define mucosal melanoma**
​
2. **Author list:** Yingxiao Shi*, Priyanka Sharma*, Jia-ren Lin, Aikaterini, Dedeilia, Tuulia Vallius, Giuseppe Tarantino, Roxanne Pelletier, Mariana L Lopez, Nil Aygün, Michael P Manos, Sonia Cohen, Aleigha R Lawless, Yi Daniel Lu, Madeline K Roelofs, Shishir M Pant, Jiajia Chen, David E Fisher, Rameen Beroukhim, Christine G Lian, Elizabeth I  Buchbinder, Peter K Sorger, Megan L. Insco**†, David Liu**†, Genevieve Boland**† 
​
3. **Please cite this data as the following:**
   To be added later
  
5. **Relevant links:** <remove links that are not relevant>  
> * BioRxiv DOI: https://doi.org/10.64898/2026.10.02.756347
> * Associated GitHub Repository: [MY-REPO](https://github.com/MY-REPO-URL)  
> * To view an archived record of this repository: [My-ZENODO-DOI](https://zenodo.org/doi/MY-ZENDODO-DOI-URL) 
> * <Other important links if applicable>
​
5. **Licenses/restrictions placed on the data:** CC-BY [creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)
​
--------------------
ACCESS THE DATASET 
--------------------
​
## File organization:   
**Each file follows the following naming convention:**    
​
Each folder corresponds to a patient sample (N). <Edit as needed if this folder structure does not fit the needs of your paper> 
 
|File Type     | Description                                                                        | Location|
|--------      | -----------------------------------------------------------------------------------|---------|
|N.ome.tif     | Stitched multiplex Orion image pyramid in ome.tif format                           | AWS     |
|N_HE.tif      | Hematoxylin and Eosin stained image of adjacent FFPE tissue section in .vsi format | AWS     |
|\_N\_HE\_/    | folder: raw image data accompanying .vsi file                                      | AWS     |
|markers.csv   | list of all markers in ome.tif image                                               | AWS     |
|N.csv         | single-cell feature table, including intensity data for all channels               | AWS     |
|N_ROI.csv     | X and Y coordinates for histologically annotated regions in CyCIF and H&E images   | AWS     |
|raw/          | folder of raw IF image data in .rcpnl format                                       | AWS     |
|segmentation/ |  folder of segmentation maps for tissue image in .tif format                       | AWS     |
​
​
## AWS Data Access  
​
Orion and HE imaging data as well as associated segmentation mask and single-cell feature table are available for download through AWS. 
​
**You will need the following bucket name:**  
```
AWS BUCKET NAME  
```
​
*For general instructions on how to download data from AWS, see: [https://zenodo.org/records/10223574](https://zenodo.org/records/10223574)*     
  
If you experience issues accessing the above AWS S3 buckets, email tissue-atlas(at)hms.harvard.edu with the subject line "bucketname: Data Access".  
​
## Other Repository 
<if applicable>  
​
## FILE LIST  
<List all files (or folders, as appropriate for dataset organization) contained in each repository, with a brief description. If you are depositing certain file types into public, standardized repositories that already include a file index & metadata, you can link to that repository instead of listing all individual files. For all other data, (on AWS, etc) list all files. >  
​
### N.ome.tif
​
|Patient or Biospecimen ID | File Name       | Location| File size |
|------- | ----------------|---------|-----------|
|ID | ID.ome.tif | AWS     | N.N GB   |
​
​
### N_HE.tif
​
|Patient or Biospecimen ID | File Name      | Location| File size|
|--------| ---------------|---------|----------|
|ID | ID.ome.tif_HE.vsi | AWS     | N.N KB |
​
​
### \_N\_HE\_/
​
|Patient or Biospecimen ID | File Name   | Location| File size|
|------- | ------------|---------|----------|
|ID | frame_t.ets | AWS     | N.N MB |
​
### markers.csv
​
|Patient or Biospecimen ID | File Name   | Synapse ID  | File size|
|------- | ----------- |------------ |----------|
|ID | markers.csv | syn12345678 | N.N bytes|
​
### N.csv
​
|Patient or Biospecimen ID | File Name   | Synapse ID | File size |
|------- | ------------|------------|-----------|
|ID | ID.csv |  |  |
​
### N_ROI.csv
​
|Patient or Biospecimen ID | File Name       | Synapse ID  | File size|
|------- | ----------------|-------------|----------|
|ID | ID_ROI.csv |  |    |
​
### raw/
​
|Patient or Biospecimen ID | Number of Files | Folder size| Location|
|------- |-----------------|------------|---------|
|ID | 13              |     |      |
​
​
### segmentation/
​
|Patient or Biospecimen ID | Number of Files | Folder size| Location|
|------- |-----------------|------------|---------|
|ID |               |     |      |
​
​
 
--------------------------
ADDITIONAL NOTES/COMMENTS
--------------------------
​
Please let **Yingxiao Shi (Yingxiao_Shi@g.harvard.edu)** know if any errors are found in this data.  
