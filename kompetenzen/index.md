---
aliases:
  - Kompetenzen
tags:
  - Glossar
  - Index
date-created: 2023-04-07
date-modified: 2023-04-07
---

# Kompetenzen

### Gesamt

```dataview 
table WITHOUT ID aliases AS Kompetenz, Erfahrung AS "Erfahrung in Jahren"
from "kompetenzen" 
SORT Erfahrung DESC
FLATTEN aliases
```

## Liste von Hardskills

```dataview 
table WITHOUT ID aliases AS Kompetenz, Erfahrung AS "Erfahrung in Jahren", Bewertung, Selbsteinschätzung, Fremdeinschätzung
from #Kompetenzen AND #Hardskills 
SORT Erfahrung DESC
FLATTEN aliases
```

## Liste von Softskills

```dataview 
table WITHOUT ID aliases AS Kompetenz, Erfahrung AS "Erfahrung in Jahren", Bewertung, Selbsteinschätzung, Fremdeinschätzung
from #Kompetenzen AND #Softskills  
SORT Erfahrung DESC
FLATTEN aliases
```
