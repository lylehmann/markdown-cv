---
aliases:
  - Lebenslauf-Datenbank
---
# Berufserfahrung

## Erfahrung in Jahren


```dataview 
TABLE  Without ID
aliases AS Beruf,
Firmenname,
Startdatum, 
Enddatum, 
Enddatum - Startdatum AS Dauer
from "berufserfahrung"  
sort Startdatum DESC
```
