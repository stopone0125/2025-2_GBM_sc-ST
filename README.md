## 2025-2_GBM_sc-ST
### Data source
1.`Desktop/SCGW_F25/Thesis_GBM/GSE84465_RAW/*.csv.gz`

I downloaded the scRNA-seq data set from the Gene Expression Omnibus (GEO).

Source : GEO accession GSE84465

  - Visit the link : https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE84465
  - Download the `GSE84465_RAW.tar` file
  - Unzip the downloaded file to access the `.csv.gz` files 

2.`Desktop/SCGW_F25/Thesis_GBM/SraRunTable.csv`

I downloaded the metadata from the NCBI Sequence Read Archive (SRA).

Source : NCBI SRA accession PRJNA330719

  - Visit the link : https://www.ncbi.nlm.nih.gov/Traces/study/?page=72&acc=PRJNA330719&o=acc_s%3Aa
    <img width="401" height="274" alt="image" src="https://github.com/user-attachments/assets/62669453-5968-4e72-b875-d0c510bd5324" />
  - As shown in the image above, click the `Metadata` button in the Download column. 

### Development environment set up
The development environment was set up using conda with Python 3.12.

A `requirements.txt` file was created to list all necessary dependencies required to run the analysis.

```bash
conda create -n scgw_f25 python=3.12 -y
conda activate scgw_f25
pip install -r requirements.txt

