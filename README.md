# BigDataInfProject
Project for the Course Big Data Infrastructure

# Austria’s Baby Deficit: How Housing Costs and Economic Pressure Are Keeping Birth Rates Low 

## Project team
- Elias Grünbacher
- Peter Kovacs
- Mario Lagger


## Story
- Austrian birth rates have been falling for decades and hit record lows in recent years
- Correlations with region, unemployment and housing prices emerge


## Planned data sources
1) Fertility / birth rate
    - Statistik Austria: Ausgewälte demographische Indikatoren für Österreich und alle NUTS-Regionen ab 2002, Gesamtfertilitätsrate (.csv)
        - https://data.statistik.gv.at/web/meta.jsp?dataset=OGD_indquot001_HVD_INDQUOTE_6

    - Statistik Austria: Ausgewälte demographische Indikatoren für Österreich und alle NUTS-Regionen ab 2002, Rohe Geburtenrate (.csv)
        - https://data.statistik.gv.at/web/meta.jsp?dataset=OGD_indquot001_HVD_INDQUOTE_3

2) Housing prices 
    - Statistik Austria: Häuserpreisindex (.ods)
        - https://www.statistik.at/statistiken/volkswirtschaft-und-oeffentliche-finanzen/preise-und-preisindizes/haeuserpreisindex-und-ooh-pi
        - https://www.statistik.at/fileadmin/pages/221/HPIMesszahlen.ods

3) Economic indicators (GRP per capita & Female labour participation)
    - Statistik Austria: GRP by NUTS3 (.ods)
        - https://www.statistik.at/en/statistics/national-economy-and-public-finance/national-accounts/regional-accounts
        - https://www.statistik.at/fileadmin/pages/226/Gross_Regional_Product_NUTS3.ods

    - Statistik Austria: Erwerbstätigkeit (.ods)
        - https://www.statistik.at/statistiken/bevoelkerung-und-soziales/gender-statistiken/erwerbstaetigkeit
        - https://www.statistik.at/fileadmin/pages/360/Tab2_erwerbstaetigenquoten_nach_alter_und_geschlecht_seit_1994.ods




## Planned data storage
- MongoDB 
    - maximum flexibility for our mixed data variety
    - simple infrastructure 
    - easily shareable


## Planned procedure
- Data cleaning and preprocessing (Python pandas)
- Data integration (Python Pandas)
- Store data in distributed system
- Apply MapReduce
- Perform analysis
- Interpret results
- Visualisation (Python matplotlib, seaborn)
- Documentation


## Expected output
- Show correlation between datasets
- Coherent storytelling narrative about the relationship between 
    - Declining fertility / birth rates in Austria.
    - Housing prices
    - Economic indicators


