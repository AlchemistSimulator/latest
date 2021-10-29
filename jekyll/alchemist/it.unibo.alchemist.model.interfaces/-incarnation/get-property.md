---
title: getProperty
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Incarnation](index.html)/[getProperty](get-property.html)



# getProperty



[jvm]\
abstract fun [getProperty](get-property.html)(node: [Node](../-node/index.html)<[T](../-node/index.html)>, molecule: [Molecule](../-molecule/index.html), property: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)



Given an [Node](../-node/index.html), an [Molecule](../-molecule/index.html) and a property expressed as a [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), returns a numeric value. If a numeric value is not deducible, Double.NaN is returned.



#### Return



a numeric value representing the property



## Parameters


jvm

| | |
|---|---|
| node | the node |
| molecule | the molecule to analyze |
| property | the property to extract |




