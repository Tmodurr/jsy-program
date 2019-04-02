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
- County Names ```UPPER```
- City Names ```Capitalized```

#### Export
- Use RGB for projector use

Layer Spec
======

#### Select project states
```sql
ST_NAME IN ( 'Uttar Pradesh', 'Uttarakhand', 'Bihar', 'Jharkhand', 'Madhya Pradesh', 'Chhattisgarh', 'Himachal Pradesh', 'Rajasthan', 'Orissa', 'Jammu And Kashmir')
```

#### Dataset extents/style

- Clip water bodies to landmasses (erase)



##### Notes from draft
- Don't overlap polys, bitch to work with transparency
- Record fonts you like, always happens like this............
- Generalized boundaries are better but make sure you snap em or use same origin 
- record title fonts 
- go back through grouping and merging layers






