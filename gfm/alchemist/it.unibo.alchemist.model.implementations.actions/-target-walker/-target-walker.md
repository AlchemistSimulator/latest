//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[TargetWalker](index.md)/[TargetWalker](-target-walker.md)

# TargetWalker

[jvm]\
open fun [TargetWalker](-target-walker.md)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()trackMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), @[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()interactingMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), interaction: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

open fun [TargetWalker](-target-walker.md)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, trackMolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), interactingMolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), interaction: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Parameters

jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction. Will be used to compute the distance to walk in every step, relying on [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)'s getRate() method. |
| trackMolecule | the molecule to track. Its value will be read when it is time to compute a new target. If it is a [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md), it will be used as-is. If it is an [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), the first two values (if they are present and they are numbers, or Strings parse-able to numbers) will be used to create a new [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md). Otherwise, the [Object](https://docs.oracle.com/javase/8/docs/api/java/lang/Object.html) bound to this [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md) will be converted to a String, and the String will be parsed using the float regular expression matcher in Javalib. |
| interactingMolecule | the molecule that decides wether or not a node is physically interacting with the node in which this action is executed, slowing this node down. The node will be considered "interacting" if such molecule is present, regardless its value. |
| speed | the speed at which this [MoveOnMap](../-move-on-map/index.md) will move |
| interaction | the higher, the more the [MoveOnMap](../-move-on-map/index.md) slows down when obstacles are found |
| range | the range in which searching for possible obstacles. Obstacles slow down the [MoveOnMap](../-move-on-map/index.md) |

[jvm]\
open fun [TargetWalker](-target-walker.md)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, trackMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), interactingMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Parameters

jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction. Will be used to compute the distance to walk in every step, relying on [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)'s getRate() method. |
| trackMolecule | the molecule to track. Its value will be read when it is time to compute a new target. If it is a [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md), it will be used as-is. If it is an [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), the first two values (if they are present and they are numbers, or Strings parse-able to numbers) will be used to create a new [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md). Otherwise, the [Object](https://docs.oracle.com/javase/8/docs/api/java/lang/Object.html) bound to this [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md) will be converted to a String, and the String will be parsed using the float regular expression matcher in Javalib. |
| interactingMolecule | the molecule that decides wether or not a node is physically interacting with the node in which this action is executed, slowing this node down. The node will be considered "interacting" if such molecule is present, regardless its value. |
| speed | the speed at which this [MoveOnMap](../-move-on-map/index.md) will move when obstacles are found |

[jvm]\
open fun [TargetWalker](-target-walker.md)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, trackMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), interactingMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md))

## Parameters

jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction. Will be used to compute the distance to walk in every step, relying on [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)'s getRate() method. |
| trackMolecule | the molecule to track. Its value will be read when it is time to compute a new target. If it is a [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md), it will be used as-is. If it is an [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), the first two values (if they are present and they are numbers, or Strings parse-able to numbers) will be used to create a new [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md). Otherwise, the [Object](https://docs.oracle.com/javase/8/docs/api/java/lang/Object.html) bound to this [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md) will be converted to a String, and the String will be parsed using the float regular expression matcher in Javalib. |
| interactingMolecule | the molecule that decides wether or not a node is physically interacting with the node in which this action is executed, slowing this node down. The node will be considered "interacting" if such molecule is present, regardless its value. |

[jvm]\
open fun [TargetWalker](-target-walker.md)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, trackMolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Parameters

jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction. Will be used to compute the distance to walk in every step, relying on [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)'s getRate() method. |
| trackMolecule | the molecule to track. Its value will be read when it is time to compute a new target. If it is a [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md), it will be used as-is. If it is an [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), the first two values (if they are present and they are numbers, or Strings parse-able to numbers) will be used to create a new [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md). Otherwise, the [Object](https://docs.oracle.com/javase/8/docs/api/java/lang/Object.html) bound to this [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md) will be converted to a String, and the String will be parsed using the float regular expression matcher in Javalib. |
| speed | the speed at which this [MoveOnMap](../-move-on-map/index.md) will move |

[jvm]\
open fun [TargetWalker](-target-walker.md)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.md)>, trackMolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))

## Parameters

jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction. Will be used to compute the distance to walk in every step, relying on [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)'s getRate() method. |
| trackMolecule | the molecule to track. Its value will be read when it is time to compute a new target. If it is a [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md), it will be used as-is. If it is an [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), the first two values (if they are present and they are numbers, or Strings parse-able to numbers) will be used to create a new [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md). Otherwise, the [Object](https://docs.oracle.com/javase/8/docs/api/java/lang/Object.html) bound to this [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md) will be converted to a String, and the String will be parsed using the float regular expression matcher in Javalib. |
