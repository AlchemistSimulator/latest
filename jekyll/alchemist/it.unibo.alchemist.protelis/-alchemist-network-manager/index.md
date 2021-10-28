---
title: AlchemistNetworkManager
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.protelis](../index.html)/[AlchemistNetworkManager](index.html)



# AlchemistNetworkManager



[jvm]\
class [AlchemistNetworkManager](index.html) : NetworkManager, [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Emulates a NetworkManager. This particular network manager does not send messages instantly. Instead, it records the last message to send, and only when [simulateMessageArrival](simulate-message-arrival.html) is called the transfer is actually done.



## Constructors


| | |
|---|---|
| [AlchemistNetworkManager](-alchemist-network-manager.html) | [jvm]<br>open fun [AlchemistNetworkManager](-alchemist-network-manager.html)(executionTime: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, program: [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>the reaction hosting the NetworkManager |
| [AlchemistNetworkManager](-alchemist-network-manager.html) | [jvm]<br>open fun [AlchemistNetworkManager](-alchemist-network-manager.html)(executionTime: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, program: [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, retentionTime: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the reaction hosting the NetworkManager |
| [AlchemistNetworkManager](-alchemist-network-manager.html) | [jvm]<br>open fun [AlchemistNetworkManager](-alchemist-network-manager.html)(executionTime: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, program: [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, retentionTime: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), distanceLossDistribution: RealDistribution)<br>the reaction hosting the NetworkManager |


## Functions


| Name | Summary |
|---|---|
| [getDistancePacketLossDistribution](get-distance-packet-loss-distribution.html) | [jvm]<br>open fun [getDistancePacketLossDistribution](get-distance-packet-loss-distribution.html)(): RealDistribution |
| [getNeighborState](index.html#-1455172944%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getNeighborState](index.html#-1455172944%2FFunctions%2F-134779887)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<DeviceUID, [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<CodePath, [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>> |
| [shareState](share-state.html) | [jvm]<br>open fun [shareState](share-state.html)(toSend: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<CodePath, [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [simulateMessageArrival](simulate-message-arrival.html) | [jvm]<br>open fun [simulateMessageArrival](simulate-message-arrival.html)(currentTime: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Simulates the arrival of the message to other nodes. |


## Properties


| Name | Summary |
|---|---|
| [neighborState](neighbor-state.html) | [jvm]<br>private open val [neighborState](neighbor-state.html): ImmutableMap<DeviceUID, [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<CodePath, [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>> |
| [retentionTime](retention-time.html) | [jvm]<br>private val [retentionTime](retention-time.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

