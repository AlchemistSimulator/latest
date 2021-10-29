//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Incarnation](index.md)/[getProperty](get-property.md)

# getProperty

[jvm]\
abstract fun [getProperty](get-property.md)(node: [Node](../-node/index.md)<[T](../-node/index.md)>, molecule: [Molecule](../-molecule/index.md), property: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)

Given an [Node](../-node/index.md), an [Molecule](../-molecule/index.md) and a property expressed as a [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), returns a numeric value. If a numeric value is not deducible, Double.NaN is returned.

#### Return

a numeric value representing the property

## Parameters

jvm

| | |
|---|---|
| node | the node |
| molecule | the molecule to analyze |
| property | the property to extract |
