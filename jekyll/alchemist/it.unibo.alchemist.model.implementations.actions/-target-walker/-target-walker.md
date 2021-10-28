---
title: TargetWalker
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[TargetWalker](index.html)/[TargetWalker](-target-walker.html)



# TargetWalker



[jvm]\
open fun [TargetWalker](-target-walker.html)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()trackMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), @[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()interactingMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), interaction: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

open fun [TargetWalker](-target-walker.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, trackMolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), interactingMolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), interaction: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction. Will be used to compute the distance to walk in every step, relying on [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)'s getRate() method. |
| trackMolecule | the molecule to track. Its value will be read when it is time to compute a new target. If it is a [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), it will be used as-is. If it is an [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), the first two values (if they are present and they are numbers, or Strings parse-able to numbers) will be used to create a new [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html). Otherwise, the [Object](https://docs.oracle.com/javase/8/docs/api/java/lang/Object.html) bound to this [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html) will be converted to a String, and the String will be parsed using the float regular expression matcher in Javalib. |
| interactingMolecule | the molecule that decides wether or not a node is physically interacting with the node in which this action is executed, slowing this node down. The node will be considered "interacting" if such molecule is present, regardless its value. |
| speed | the speed at which this [MoveOnMap](../-move-on-map/index.html) will move |
| interaction | the higher, the more the [MoveOnMap](../-move-on-map/index.html) slows down when obstacles are found |
| range | the range in which searching for possible obstacles. Obstacles slow down the [MoveOnMap](../-move-on-map/index.html) |





[jvm]\
open fun [TargetWalker](-target-walker.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, trackMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), interactingMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction. Will be used to compute the distance to walk in every step, relying on [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)'s getRate() method. |
| trackMolecule | the molecule to track. Its value will be read when it is time to compute a new target. If it is a [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), it will be used as-is. If it is an [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), the first two values (if they are present and they are numbers, or Strings parse-able to numbers) will be used to create a new [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html). Otherwise, the [Object](https://docs.oracle.com/javase/8/docs/api/java/lang/Object.html) bound to this [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html) will be converted to a String, and the String will be parsed using the float regular expression matcher in Javalib. |
| interactingMolecule | the molecule that decides wether or not a node is physically interacting with the node in which this action is executed, slowing this node down. The node will be considered "interacting" if such molecule is present, regardless its value. |
| speed | the speed at which this [MoveOnMap](../-move-on-map/index.html) will move when obstacles are found |





[jvm]\
open fun [TargetWalker](-target-walker.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, trackMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), interactingMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html))



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction. Will be used to compute the distance to walk in every step, relying on [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)'s getRate() method. |
| trackMolecule | the molecule to track. Its value will be read when it is time to compute a new target. If it is a [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), it will be used as-is. If it is an [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), the first two values (if they are present and they are numbers, or Strings parse-able to numbers) will be used to create a new [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html). Otherwise, the [Object](https://docs.oracle.com/javase/8/docs/api/java/lang/Object.html) bound to this [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html) will be converted to a String, and the String will be parsed using the float regular expression matcher in Javalib. |
| interactingMolecule | the molecule that decides wether or not a node is physically interacting with the node in which this action is executed, slowing this node down. The node will be considered "interacting" if such molecule is present, regardless its value. |





[jvm]\
open fun [TargetWalker](-target-walker.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, trackMolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction. Will be used to compute the distance to walk in every step, relying on [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)'s getRate() method. |
| trackMolecule | the molecule to track. Its value will be read when it is time to compute a new target. If it is a [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), it will be used as-is. If it is an [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), the first two values (if they are present and they are numbers, or Strings parse-able to numbers) will be used to create a new [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html). Otherwise, the [Object](https://docs.oracle.com/javase/8/docs/api/java/lang/Object.html) bound to this [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html) will be converted to a String, and the String will be parsed using the float regular expression matcher in Javalib. |
| speed | the speed at which this [MoveOnMap](../-move-on-map/index.html) will move |





[jvm]\
open fun [TargetWalker](-target-walker.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)>, trackMolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction. Will be used to compute the distance to walk in every step, relying on [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)'s getRate() method. |
| trackMolecule | the molecule to track. Its value will be read when it is time to compute a new target. If it is a [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), it will be used as-is. If it is an [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), the first two values (if they are present and they are numbers, or Strings parse-able to numbers) will be used to create a new [it.unibo.alchemist.model.interfaces.GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html). Otherwise, the [Object](https://docs.oracle.com/javase/8/docs/api/java/lang/Object.html) bound to this [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html) will be converted to a String, and the String will be parsed using the float regular expression matcher in Javalib. |




