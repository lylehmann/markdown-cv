---
aliases:
  - Miro
tags:
  - Hardskills
  - Kompetenzen
Erfahrung: 0.6
---
# Miro

```dataview
TABLE WITHOUT ID aliases AS Berufserfahrung, Firmenname,
Enddatum - Startdatum AS Dauer
WHERE contains(tags, "Miro")
SORT ASC
```