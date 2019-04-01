# jsy-program
Conference work for India's Janani Suraksha Yojana (JSY) program


Data Sources
======

#### [State Boundary Source](https://services8.arcgis.com/8p4cTJERnT5sCxpI/arcgis/rest/services/India_State_Boundary/FeatureServer/0) 

#### [External Countries boundaries](https://www.naturalearthdata.com/downloads/10m-cultural-vectors/)


Map Spec
======

#### CRS
```Asia_Lambert_Conformal_Conic Projection: Lambert_Conformal_Conic```

#### Labeling
- Label in .ai
- County Names ```sql UPPER```
- City Names ```sql Capitalized```

#### Export
- Use RGB for projector use

Layer Spec
======

#### Select project states
```sql
ST_NAME IN ( 'Uttar Pradesh', 'Uttarakhand', 'Bihar', 'Jharkhand', 'Madhya Pradesh', 'Chhattisgarh', 'Himachal Pradesh', 'Rajasthan', 'Orissa', 'Jammu And Kashmir')
```
