---
title: getWider
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Context](index.html)/[getWider](get-wider.html)



# getWider



[jvm]\
open fun [getWider](get-wider.html)(c1: [Context](index.html), c2: [Context](index.html)): [Context](index.html)



#### Return



the wider (more general) between the two: if either one is GLOBAL, then GLOBAL is returned. Otherwise, if either one is NEIGHBORHOOD, NEIGHBORHOOD is returned. Otherwise, LOCAL is returned.



## Parameters


jvm

| | |
|---|---|
| c1 | context to compare |
| c2 | other context to compare |




