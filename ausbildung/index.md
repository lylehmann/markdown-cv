---
aliases:
  - Lebenslauf-Datenbank
---
# Ausbildung

## Erfahrung in Jahren


```dataview 
TABLE  Without ID
aliases AS Ausbildung,
Firmenname,
Startdatum, 
Enddatum, 
Enddatum - Startdatum AS Dauer
from "ausbildung"
sort Startdatum DESC
```

