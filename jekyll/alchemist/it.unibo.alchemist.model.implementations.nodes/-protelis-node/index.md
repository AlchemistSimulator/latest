---
title: ProtelisNode
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.nodes](../index.html)/[ProtelisNode](index.html)



# ProtelisNode



[jvm]\
class [ProtelisNode](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](index.html)>?> : [AbstractNode](../-abstract-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> , DeviceUID, ExecutionEnvironment



## Parameters


jvm

| | |
|---|---|
| <P> | Position type |



## Constructors


| | |
|---|---|
| [ProtelisNode](-protelis-node.html) | [jvm]<br>open fun [ProtelisNode](-protelis-node.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](index.html)>)<br>Builds a new [ProtelisNode](index.html). |


## Functions


| Name | Summary |
|---|---|
| [addNetworkManger](add-network-manger.html) | [jvm]<br>open fun [addNetworkManger](add-network-manger.html)(program: [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, networkManager: [AlchemistNetworkManager](../../it.unibo.alchemist.protelis/-alchemist-network-manager/index.html))<br>Adds a new [AlchemistNetworkManager](../../it.unibo.alchemist.protelis/-alchemist-network-manager/index.html). |
| [addReaction](../-abstract-node/add-reaction.html) | [jvm]<br>fun [addReaction](../-abstract-node/add-reaction.html)(reactionToAdd: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)>) |
| [cloneNode](clone-node.html) | [jvm]<br>open fun [cloneNode](clone-node.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [ProtelisNode](index.html)<[P](index.html)><br>abstract fun [cloneNode](../../it.unibo.alchemist.model.interfaces/-node/clone-node.html)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)> |
| [commit](commit.html) | [jvm]<br>open fun [commit](commit.html)() |
| [compareTo](../-abstract-node/compare-to.html) | [jvm]<br>fun [compareTo](../-abstract-node/compare-to.html)(other: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](../-abstract-node/contains.html) | [jvm]<br>open fun [contains](../-abstract-node/contains.html)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](../-abstract-node/equals.html) | [jvm]<br>fun [equals](../-abstract-node/equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../-abstract-node/for-each.html) | [jvm]<br>fun [forEach](../-abstract-node/for-each.html)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [get](get.html) | [jvm]<br>open fun [get](get.html)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>open fun [get](get.html)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), defaultValue: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [getConcentration](../-abstract-node/get-concentration.html) | [jvm]<br>open fun [getConcentration](../-abstract-node/get-concentration.html)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html) |
| [getContents](../-abstract-node/get-contents.html) | [jvm]<br>open fun [getContents](../-abstract-node/get-contents.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), [T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)> |
| [getId](../-homogeneous-physical-pedestrian2-d/index.html#2063123767%2FFunctions%2F-134779887) | [jvm]<br>fun [getId](../-homogeneous-physical-pedestrian2-d/index.html#2063123767%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../-abstract-node/get-molecule-count.html) | [jvm]<br>open fun [getMoleculeCount](../-abstract-node/get-molecule-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getNetworkManager](get-network-manager.html) | [jvm]<br>open fun [getNetworkManager](get-network-manager.html)(program: [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [AlchemistNetworkManager](../../it.unibo.alchemist.protelis/-alchemist-network-manager/index.html)<br>the [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.html) |
| [getReactions](../-homogeneous-physical-pedestrian2-d/index.html#-301186114%2FFunctions%2F-134779887) | [jvm]<br>fun [getReactions](../-homogeneous-physical-pedestrian2-d/index.html#-301186114%2FFunctions%2F-134779887)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)>> |
| [has](has.html) | [jvm]<br>open fun [has](has.html)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](../-abstract-node/hash-code.html) | [jvm]<br>fun [hashCode](../-abstract-node/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../-abstract-node/iterator.html) | [jvm]<br>fun [iterator](../-abstract-node/iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)>><br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)> |
| [keySet](key-set.html) | [jvm]<br>open fun [keySet](key-set.html)(): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)> |
| [put](put.html) | [jvm]<br>open fun [put](put.html)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), v: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [putField](put-field.html) | [jvm]<br>open fun [putField](put-field.html)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), v: Field): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Writes a Map representation of the Field on the environment. |
| [remove](remove.html) | [jvm]<br>open fun [remove](remove.html)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [removeConcentration](../-abstract-node/remove-concentration.html) | [jvm]<br>open fun [removeConcentration](../-abstract-node/remove-concentration.html)(moleculeToRemove: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [removeReaction](../-abstract-node/remove-reaction.html) | [jvm]<br>fun [removeReaction](../-abstract-node/remove-reaction.html)(reactionToRemove: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)>) |
| [setConcentration](../-abstract-node/set-concentration.html) | [jvm]<br>open fun [setConcentration](../-abstract-node/set-concentration.html)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), concentration: [T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)) |
| [setup](setup.html) | [jvm]<br>open fun [setup](setup.html)() |
| [spliterator](../-abstract-node/spliterator.html) | [jvm]<br>fun [spliterator](../-abstract-node/spliterator.html)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)>><br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)> |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Properties


| Name | Summary |
|---|---|
| [networkManagers](network-managers.html) | [jvm]<br>private val [networkManagers](network-managers.html): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, [AlchemistNetworkManager](../../it.unibo.alchemist.protelis/-alchemist-network-manager/index.html)> |

