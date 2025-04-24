# **BComputational Drug Discovery**


## **ChEMBL Database**

The [*ChEMBL Database*](https://www.ebi.ac.uk/chembl/) is a database that contains curated bioactivity data of more than 2 million compounds. It is compiled from more than 76,000 documents, 1.2 million assays and the data spans 13,000 targets and 1,800 cells and 33,000 indications.
[Data as of March 25, 2020; ChEMBL version 26].

## **Libraries**

Create virtual environment
```python
python -m venv .bioinfo

.bioinfo\Scripts\activate (Windows)
source .bioinfo/bin/activate (iOS)
```

1) *chembl_webresource_client* : the ChEMBL web service package allows retrieving bioactivity data from the ChEMBL Database.
