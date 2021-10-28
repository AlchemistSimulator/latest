//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.molecules](../index.md)/[LsaMolecule](index.md)/[LsaMolecule](-lsa-molecule.md)

# LsaMolecule

[jvm]\
open fun [LsaMolecule](-lsa-molecule.md)()

Empty molecule, no arguments.

[jvm]\
open fun [LsaMolecule](-lsa-molecule.md)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()listArgs: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)>)

Builds a new LsaMolecule by interpreting a list of IExpressions. Dramatically faster than parsing, slower than copy.

## Parameters

jvm

| | |
|---|---|
| listArgs | the list of IExpressions |

[jvm]\
open fun [LsaMolecule](-lsa-molecule.md)(m: [LsaMolecule](index.md))

Very fast constructor, produces a copy of an LsaMolecule. Use whenever possible.

## Parameters

jvm

| | |
|---|---|
| m | the LsaMolecule to copy |

[jvm]\
open fun [LsaMolecule](-lsa-molecule.md)(argsString: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))

Builds a LsaMolecule by parsing the passed String. Slow, use only if strictly needed.

## Parameters

jvm

| | |
|---|---|
| argsString | the String to parse |

[jvm]\
open fun [LsaMolecule](-lsa-molecule.md)(argsString: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), description: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))

Builds a LsaMolecule by parsing the passed String. Slow, use only if strictly needed.

## Parameters

jvm

| | |
|---|---|
| argsString | the String to parse |
| description | a String to append at the end of the LSA. This is a special item, and can carry any type of String. It will be treated internally as a single literal or variable |
