---
title: SAPEREWalkerRiseGradient
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[SAPEREWalkerRiseGradient](index.html)/[SAPEREWalkerRiseGradient](-s-a-p-e-r-e-walker-rise-gradient.html)



# SAPEREWalkerRiseGradient



[jvm]\
open fun [SAPEREWalkerRiseGradient](-s-a-p-e-r-e-walker-rise-gradient.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>, speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), interaction: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), templateLSA: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), neighPos: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction (used to compute the movement length) |
| speed | the average speed of the node |
| interaction | the interaction factor |
| range | the interaction range |
| templateLSA | the LSA template to follow |
| neighPos | the position in the template LSA that contains the next hop |





[jvm]\
open fun [SAPEREWalkerRiseGradient](-s-a-p-e-r-e-walker-rise-gradient.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>, tag: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), interaction: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), templateLSA: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), neighPos: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction (used to compute the movement length) |
| tag | the molecule which identifies the interacting nodes |
| speed | the average speed of the node |
| interaction | the interaction factor |
| range | the interaction range |
| templateLSA | the LSA template to follow |
| neighPos | the position in the template LSA that contains the next hop |




