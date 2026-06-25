# CareSense: Healthcare Readmission Analytics

A data analytics project analyzing CMS Hospital Readmissions 
Reduction Program (HRRP) data to identify readmission patterns across 3,000+ U.S. hospitals.

## Dataset
Source: [CMS Provider Data](https://data.cms.gov/provider-data/dataset/9n3s-kdb3)  
File: `data/raw/readmissions.csv` (not tracked in Git — download manually)

## Setup

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```