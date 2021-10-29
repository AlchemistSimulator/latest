//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.nodes](../index.md)/[ProtelisNode](index.md)

# ProtelisNode

[jvm]\
class [ProtelisNode](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../../it.unibo.alchemist.protelis/-alchemist-execution-context/index.md)>?> : [AbstractNode](../-abstract-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> , DeviceUID, ExecutionEnvironment

## Parameters

jvm

| | |
|---|---|
| <P> | Position type |

## Constructors

| | |
|---|---|
| [ProtelisNode](-protelis-node.md) | [jvm]<br>open fun [ProtelisNode](-protelis-node.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.protelis/-alchemist-execution-context/index.md)>)<br>Builds a new [ProtelisNode](index.md). |

## Functions

| Name | Summary |
|---|---|
| [addNetworkManger](add-network-manger.md) | [jvm]<br>open fun [addNetworkManger](add-network-manger.md)(program: [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, networkManager: [AlchemistNetworkManager](../../it.unibo.alchemist.protelis/-alchemist-network-manager/index.md))<br>Adds a new [AlchemistNetworkManager](../../it.unibo.alchemist.protelis/-alchemist-network-manager/index.md). |
| [addReaction](../-abstract-node/add-reaction.md) | [jvm]<br>fun [addReaction](../-abstract-node/add-reaction.md)(reactionToAdd: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>) |
| [cloneNode](clone-node.md) | [jvm]<br>open fun [cloneNode](clone-node.md)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [ProtelisNode](index.md)<[P](../../it.unibo.alchemist.protelis/-alchemist-execution-context/index.md)><br>abstract fun [cloneNode](../../it.unibo.alchemist.model.interfaces/-node/clone-node.md)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)> |
| [commit](commit.md) | [jvm]<br>open fun [commit](commit.md)() |
| [compareTo](../-abstract-node/compare-to.md) | [jvm]<br>fun [compareTo](../-abstract-node/compare-to.md)(other: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](../-abstract-node/contains.md) | [jvm]<br>open fun [contains](../-abstract-node/contains.md)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](../-abstract-node/equals.md) | [jvm]<br>fun [equals](../-abstract-node/equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../-abstract-node/for-each.md) | [jvm]<br>fun [forEach](../-abstract-node/for-each.md)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [get](get.md) | [jvm]<br>open fun [get](get.md)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>open fun [get](get.md)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), defaultValue: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [getConcentration](../-abstract-node/get-concentration.md) | [jvm]<br>open fun [getConcentration](../-abstract-node/get-concentration.md)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md) |
| [getContents](../-abstract-node/get-contents.md) | [jvm]<br>open fun [getContents](../-abstract-node/get-contents.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), [T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)> |
| [getId](../-homogeneous-physical-pedestrian2-d/index.md#2063123767%2FFunctions%2F-267951372) | [jvm]<br>fun [getId](../-homogeneous-physical-pedestrian2-d/index.md#2063123767%2FFunctions%2F-267951372)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../-abstract-node/get-molecule-count.md) | [jvm]<br>open fun [getMoleculeCount](../-abstract-node/get-molecule-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getNetworkManager](get-network-manager.md) | [jvm]<br>open fun [getNetworkManager](get-network-manager.md)(program: [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [AlchemistNetworkManager](../../it.unibo.alchemist.protelis/-alchemist-network-manager/index.md)<br>the [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.md) |
| [getReactions](../-homogeneous-physical-pedestrian2-d/index.md#-301186114%2FFunctions%2F-267951372) | [jvm]<br>fun [getReactions](../-homogeneous-physical-pedestrian2-d/index.md#-301186114%2FFunctions%2F-267951372)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>> |
| [has](has.md) | [jvm]<br>open fun [has](has.md)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](../-abstract-node/hash-code.md) | [jvm]<br>fun [hashCode](../-abstract-node/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../-abstract-node/iterator.md) | [jvm]<br>fun [iterator](../-abstract-node/iterator.md)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>><br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)> |
| [keySet](key-set.md) | [jvm]<br>open fun [keySet](key-set.md)(): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)> |
| [put](put.md) | [jvm]<br>open fun [put](put.md)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), v: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [putField](put-field.md) | [jvm]<br>open fun [putField](put-field.md)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), v: Field): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Writes a Map representation of the Field on the environment. |
| [remove](remove.md) | [jvm]<br>open fun [remove](remove.md)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [removeConcentration](../-abstract-node/remove-concentration.md) | [jvm]<br>open fun [removeConcentration](../-abstract-node/remove-concentration.md)(moleculeToRemove: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [removeReaction](../-abstract-node/remove-reaction.md) | [jvm]<br>fun [removeReaction](../-abstract-node/remove-reaction.md)(reactionToRemove: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>) |
| [setConcentration](../-abstract-node/set-concentration.md) | [jvm]<br>open fun [setConcentration](../-abstract-node/set-concentration.md)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), concentration: [T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)) |
| [setup](setup.md) | [jvm]<br>open fun [setup](setup.md)() |
| [spliterator](../-abstract-node/spliterator.md) | [jvm]<br>fun [spliterator](../-abstract-node/spliterator.md)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>><br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)> |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Properties

| Name | Summary |
|---|---|
| [networkManagers](network-managers.md) | [jvm]<br>private val [networkManagers](network-managers.md): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, [AlchemistNetworkManager](../../it.unibo.alchemist.protelis/-alchemist-network-manager/index.md)> |
