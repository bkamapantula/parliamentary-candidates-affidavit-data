# Parliamentary Candidates Affidavit Data
Data scraped from http://myneta.info/ for years 2004 to 2019 general elections.

```CSV
State,Constituency,ID,Candidate,Party,CriminalCases,Education,TotalAssets,TotalLiabilities,Year,Age,Cash,Jewellerygivedetailsweightvalue,AgriculturalLand,NonAgriculturalLand,CommercialBuildings,ResidentialBuildings,Women,Winner,ConstituencyType,ParentInfo,ReturningCandidate,unique_id
```

All columns except `unique_id` are from http://myneta.info/ website. `unique_id` is a derived column assigned for each candidate using string matching and approximation algorithms.

`unique_id` is useful to track changes in candidates wealth (assets, liabilities, cash, jewellery etc.), land over the years.

## Sample data

```CSV
WEST BENGAL,MATHURAPUR,14020,Amitav Naskar,New Democratic Party of India,0,Post Graduate,1665000,0,2019,33,100000,35000,NA,1500000,NA,NA,0,NA,SC,Amarendra Nath Naskar,0,27325
WEST BENGAL,MATHURAPUR,14022,Pronab Kumar Jatua,IND,0,10th Pass,1863644,600000,2019,57,25000,180000,1550000,NA,NA,NA,0,NA,SC,Pravash Chandra Jatua,0,27324
WEST BENGAL,MATHURAPUR,12745,Choudhury Mohan Jatua,AITC,0,Post Graduate,10667304,0,2019,80,66000,435000,450000,NA,NA,4325000,0,NA,SC,Late Parameswar Jatua,1,27323
WEST BENGAL,MATHURAPUR,12744,Purna Chandra Naiya,SUCI(C),0,Graduate Professional,8102832,0,2019,49,7500,115500,600000,NA,NA,4000000,0,NA,SC,Niran Naiya Alisa Niranjan Naiya,0,27322
```

# About data

- ADR (Association for Democratic Reforms) made affidavit data available for 7928 parliamentary candidates out of 8026 polled candidates.
- Certain portions of a candidate's affidavit data is erroneous (e.g. `4` or `1` for missing age values) due to either inaccurate data entry during affidavit filing or during the data conversion (from analog to digital) or missing age data (in which case the value is `0`).

# Unique ID creation methodology

To be expanded
