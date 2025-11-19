# Final Project — Best Neighborhood in Pittsburgh
## One-Sentence Summary
A data-driven analysis identifying the most livable neighborhood in Pittsburgh based on housing affordability, recreational access, public facilities, and parking availability.

## Project Overview
Our project explores which neighborhood in Pittsburgh can be considered the **“best”** using data from the Western Pennsylvania Regional Data Center (WPRDC).  
We define “best” as the **best for family life**.
Unlike most of other groups that typically determine a topic before identifying relevant metrics, we began by selecting several metrics of interest and subsequently derived our topic from the similarities and relationships among them.

## Group Name: JoJo

## Group Members
- Hao Wang — haw102@pitt.edu  
- Daniel Contreras — dac518@pitt.edu  
- Daniel Cintrón — dac491@pitt.edu  
- Farouk Boudjemaa — fab73@pitt.edu  

## Datasets Used
- Housing value - 
- Playgrounds - https://data.wprdc.org/dataset/playgrounds
- City of Pittsburgh facilities - https://data.wprdc.org/dataset/city-of-pittsburgh-facilities
- Parking space counts and Rates

## Neighborhood Comparision and Conclusion

**Playgrounds** (`farouk/farouk.ipynb`, `playgrounds.csv`)  
- Squirrel Hill South — 8 playgrounds  
- Beechview — 5  
- South Side Slopes — 5  
- Allegheny Center — 4  
- Highland Park — 4  

**Affordable Homes** (`danny/danny.ipynb`, `house_value.csv`, units in $300k–$399k range)  
- Squirrel Hill South — 593 homes  
- Point Breeze — 350  
- Squirrel Hill North — 342  
- Shadyside — 327  
- Highland Park — 293  

**City Facilities** (`hao/hao.ipynb`, `City Facilities.csv`)  
- Highland Park — 30 facilities  
- Squirrel Hill South — 29  
- Perry North — 20  
- Brookline — 19  
- Strip District — 15  

**Parking Availability** (`dac491/FINAL_DAC491-submetric.ipynb`, `parkingspace_rates.csv`, largest individual lots)  
- 421 - Northside — 757 spaces (on-street, $1.00/hr)  
- 403 - Uptown — 756 spaces (on-street, $1.50/hr)  
- 415 - SS & SSW — 707 spaces (on-street, $1.50/hr)  
- 403 - Uptown — 690 spaces (on-street, $1.50/hr)  
- 415 - SS & SSW — 670 spaces (on-street, $1.50/hr)  

### Conclusion

Taken together, the four submetrics position Squirrel Hill South as the most balanced neighborhood and the "best neighborhoodfor family life" in Pittsburgh. It leads in playground access and mid-priced housing, and it stays competitive in municipal facilities. 
Uptown, the Northside, and the South Side have plenty of parking, but they’re still behind when it comes to family-friendly spaces and a good mix of housing. Highland Park scores well on facilities and stays competitive, but Squirrel Hill South still offers the best overall balance for everyday living.

