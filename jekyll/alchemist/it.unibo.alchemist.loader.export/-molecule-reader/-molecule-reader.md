---
title: MoleculeReader
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.export](../index.html)/[MoleculeReader](index.html)/[MoleculeReader](-molecule-reader.html)



# MoleculeReader



[jvm]\
open fun [MoleculeReader](-molecule-reader.html)(molecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), property: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, filter: [FilteringPolicy](../-filtering-policy/index.html), aggregators: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)>)



## Parameters


jvm

| | |
|---|---|
| molecule | the target molecule |
| property | the target property |
| incarnation | the target incarnation |
| filter | the [FilteringPolicy](../-filtering-policy/index.html) to use |
| aggregators | the names of the UnivariateStatistic to use for aggregating data. If an empty list is passed, then the values will be logged indipendently for each node. |




