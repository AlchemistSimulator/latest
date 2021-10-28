//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Context](index.md)/[getWider](get-wider.md)

# getWider

[jvm]\
open fun [getWider](get-wider.md)(c1: [Context](index.md), c2: [Context](index.md)): [Context](index.md)

#### Return

the wider (more general) between the two: if either one is GLOBAL, then GLOBAL is returned. Otherwise, if either one is NEIGHBORHOOD, NEIGHBORHOOD is returned. Otherwise, LOCAL is returned.

## Parameters

jvm

| | |
|---|---|
| c1 | context to compare |
| c2 | other context to compare |
