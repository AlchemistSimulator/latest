---
title: isLocallyConsistent
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[LinkingRule](index.html)/[isLocallyConsistent](is-locally-consistent.html)



# isLocallyConsistent



[jvm]\
abstract fun [isLocallyConsistent](is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)



Some rules may require to be evaluated against multiple nodes until the situations gets consistent. For instance, a rule that connects the closest 10 nodes must be evaluated multiple times to get to the correct result (this is because a change in one neighbor may require a disconnection from another node to maintain exactly 10 connections). Most rules do not need such machinery (e.g., connecting to nodes within some statically defined range).



#### Return



true if this rule does not need to be recursively re-applied to neighbors to ensure global consistency.




