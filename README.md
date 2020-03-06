# mysql_mongodb_rgph
MYSQL/MONGODB RGPH PROJECT

The objective of this project is to set up a relational database (MySQL) and another NoSQL (MongoDB) and then query them.

The content of the DBs will be made up of the indicators of the General Census of Population and Housing of Morocco 2014 (RGPH 2014) available on the HCP website via the following link: http://rgphentableaux.hcp.ma/Default1/.
These indicators are divided into 6 themes:

- Demography (demographie)
- Handicap (handicap)
- Education and literacy (education et analphabetisme)
- Local languages used (Langues locales)
- Activity and employment (Activite et emploi)
- Housing conditions ( Conditions d'habitat )

Each theme, presented at different geographical scales (municipal, provincial, regional and national), includes a set of attributes, which are themselves broken down by gender (male and female) and by territorial category (urban and rural).

In this project, the integration of the data in the database will be done at the level of the finest division (commune), the other higher geographical levels (province, region and national) will be calculated directly by aggregation using the appropriate functions and pipelines.
