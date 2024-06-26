---
aliases:
  - Behinderungen
tags:
  - Kompetenzen
  - Hardskills
Erfahrung: 6
---

# Behinderungen

```dataview
TABLE aliases AS Berufserfahrung, Firmenname,
Enddatum - Startdatum AS Dauer
WHERE contains(tags, "Behinderungen")
SORT ASC
```