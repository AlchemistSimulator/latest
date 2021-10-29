//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.reactions](../index.md)/[SAPEREGradient](index.md)/[SAPEREGradient](-s-a-p-e-r-e-gradient.md)

# SAPEREGradient

[jvm]\
open fun [SAPEREGradient](-s-a-p-e-r-e-gradient.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>, [P](../../it.unibo.alchemist.model.implementations.actions/-lsa-ascending-gradient-dist/index.md)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), sourceTemplate: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md), gradientTemplate: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md), valuePosition: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), expression: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), contextTemplate: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md), gradThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), timeDistribution: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>)

Builds a new SAPERE Gradient.

## Parameters

jvm

| | |
|---|---|
| environment | the current environment |
| node | the node where this reaction is scheduled |
| sourceTemplate | a template ILsaMolecule representing the source |
| gradientTemplate | a template ILsaMolecule representing the gradient. ALL the variables MUST be the same of sourceTemplate: no un-instanced variables are admitted when inserting tuples into nodes |
| valuePosition | the point at which the computation of the new values should be inserted. All the data after this position will be considered "additional information" propagated by the source. All the values before this one, instead, will be used to distinct different gradients |
| expression | the expression to use in order to calculate the new gradient value. #T and #D are admitted, plus every variable present in the gradient before valuePosition, and every variable matched by the contextTemplate |
| contextTemplate | a template ILsaMolecule. It can be used to match some contents of the local node in order to have local information to use in the gradient value computation |
| gradThreshold | if the value of the gradient grows above this threshold, the gradient evaporates |
| timeDistribution | Markovian Rate |

[jvm]\
open fun [SAPEREGradient](-s-a-p-e-r-e-gradient.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>, [P](../../it.unibo.alchemist.model.implementations.actions/-lsa-ascending-gradient-dist/index.md)>, n: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), td: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>, sourceTemplate: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), gradientTemplate: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), valuePosition: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), expression: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), contextTemplate: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), gradThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

Builds a new SAPERE Gradient. This constructor is slower, and is provided for compatibility with the YAML-based Alchemist loader. It should be avoided when possible, by relying on the other constructor instead.

## Parameters

jvm

| | |
|---|---|
| env | the current environment |
| n | the node where this reaction is scheduled |
| sourceTemplate | a template ILsaMolecule representing the source |
| gradientTemplate | a template ILsaMolecule representing the gradient. ALL the variables MUST be the same of sourceTemplate: no un-instanced variables are admitted when inserting tuples into nodes |
| valuePosition | the point at which the computation of the new values should be inserted. All the data after this position will be considered "additional information" propagated by the source. All the values before this one, instead, will be used to distinct different gradients |
| expression | the expression to use in order to calculate the new gradient value. #T and #D are admitted, plus every variable present in the gradient before valuePosition, and every variable matched by the contextTemplate |
| contextTemplate | a template ILsaMolecule. It can be used to match some contents of the local node in order to have local information to use in the gradient value computation |
| gradThreshold | if the value of the gradient grows above this threshold, the gradient evaporates |
| td | Markovian Rate |
