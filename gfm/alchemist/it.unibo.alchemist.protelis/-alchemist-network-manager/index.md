//[alchemist](../../../index.md)/[it.unibo.alchemist.protelis](../index.md)/[AlchemistNetworkManager](index.md)

# AlchemistNetworkManager

[jvm]\
class [AlchemistNetworkManager](index.md) : NetworkManager, [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Emulates a NetworkManager. This particular network manager does not send messages instantly. Instead, it records the last message to send, and only when [simulateMessageArrival](simulate-message-arrival.md) is called the transfer is actually done.

## Constructors

| | |
|---|---|
| [AlchemistNetworkManager](-alchemist-network-manager.md) | [jvm]<br>open fun [AlchemistNetworkManager](-alchemist-network-manager.md)(executionTime: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, program: [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>the reaction hosting the NetworkManager |
| [AlchemistNetworkManager](-alchemist-network-manager.md) | [jvm]<br>open fun [AlchemistNetworkManager](-alchemist-network-manager.md)(executionTime: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, program: [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, retentionTime: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the reaction hosting the NetworkManager |
| [AlchemistNetworkManager](-alchemist-network-manager.md) | [jvm]<br>open fun [AlchemistNetworkManager](-alchemist-network-manager.md)(executionTime: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, program: [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, retentionTime: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), distanceLossDistribution: RealDistribution)<br>the reaction hosting the NetworkManager |

## Functions

| Name | Summary |
|---|---|
| [getDistancePacketLossDistribution](get-distance-packet-loss-distribution.md) | [jvm]<br>open fun [getDistancePacketLossDistribution](get-distance-packet-loss-distribution.md)(): RealDistribution |
| [getNeighborState](index.md#-1455172944%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getNeighborState](index.md#-1455172944%2FFunctions%2F-267951372)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<DeviceUID, [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<CodePath, [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>> |
| [shareState](share-state.md) | [jvm]<br>open fun [shareState](share-state.md)(toSend: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<CodePath, [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [simulateMessageArrival](simulate-message-arrival.md) | [jvm]<br>open fun [simulateMessageArrival](simulate-message-arrival.md)(currentTime: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Simulates the arrival of the message to other nodes. |

## Properties

| Name | Summary |
|---|---|
| [neighborState](neighbor-state.md) | [jvm]<br>private open val [neighborState](neighbor-state.md): ImmutableMap<DeviceUID, [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<CodePath, [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>> |
| [retentionTime](retention-time.md) | [jvm]<br>private val [retentionTime](retention-time.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
