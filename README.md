# parliamentary-candidates-affidavit-data
Data scraped from myneta.info for years 2004 to 2019 general elections.

```CSV
State,Constituency,ID,Candidate,Party,CriminalCases,Education,TotalAssets,TotalLiabilities,Year,Age,Cash,Jewellerygivedetailsweightvalue,AgriculturalLand,NonAgriculturalLand,CommercialBuildings,ResidentialBuildings,Women,Winner,ConstituencyType,ParentInfo,ReturningCandidate,unique_id
```

All columns except `unique_id` are from myneta.info website. `unique_id` is a derived column assigned for each candidate using string matching and approximation algorithms.

`unique_id` is useful to track changes in candidates wealth (assets, liabilities, cash, jewellery etc.), land over the years.
