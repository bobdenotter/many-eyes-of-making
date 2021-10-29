# Locations, Lore and Items

## Locations

```dataview
table x
from "Locations and Items" and -#item
sort file.name ASC 
```

## Lore

```dataview
table x
from "Lore"
sort file.name ASC 
```

## Items

```dataview
table owner
from "Locations and Items" and #item
sort file.name ASC 
```