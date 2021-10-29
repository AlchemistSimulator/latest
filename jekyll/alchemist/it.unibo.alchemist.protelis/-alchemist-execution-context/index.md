---
title: AlchemistExecutionContext
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.protelis](../index.html)/[AlchemistExecutionContext](index.html)



# AlchemistExecutionContext



[jvm]\
class [AlchemistExecutionContext](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>?> : AbstractExecutionContext<[AlchemistExecutionContext](index.html)<[P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>> , SpatiallyEmbeddedDevice<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> , LocalizedDevice, TimeAwareDevice



## Parameters


jvm

| | |
|---|---|
| <P> | position type |



## Constructors


| | |
|---|---|
| [AlchemistExecutionContext](-alchemist-execution-context.html) | [jvm]<br>open fun [AlchemistExecutionContext](-alchemist-execution-context.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, localNode: [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)<[P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, random: RandomGenerator, networkManager: [AlchemistNetworkManager](../-alchemist-network-manager/index.html))<br>the simulation [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html) |


## Functions


| Name | Summary |
|---|---|
| [buildField](index.html#1729644764%2FFunctions%2F-134779887) | [jvm]<br>fun <[T](index.html#1729644764%2FFunctions%2F-134779887), [R](index.html#1729644764%2FFunctions%2F-134779887)> [buildField](index.html#1729644764%2FFunctions%2F-134779887)(computeValue: ([T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)) -> [R](index.html#1729644764%2FFunctions%2F-134779887), localValue: [T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)): Field<[R](index.html#1729644764%2FFunctions%2F-134779887)> |
| [buildFieldDeferred](index.html#819827614%2FFunctions%2F-134779887) | [jvm]<br>fun <[T](index.html#819827614%2FFunctions%2F-134779887), [R](index.html#819827614%2FFunctions%2F-134779887)> [buildFieldDeferred](index.html#819827614%2FFunctions%2F-134779887)(computeValue: ([T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)) -> [R](index.html#1729644764%2FFunctions%2F-134779887), currentLocal: [T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html), toBeSent: [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)>): Field<[R](index.html#1729644764%2FFunctions%2F-134779887)> |
| [commit](index.html#-1965213452%2FFunctions%2F-134779887) | [jvm]<br>fun [commit](index.html#-1965213452%2FFunctions%2F-134779887)() |
| [distanceTo](distance-to.html) | [jvm]<br>open fun [distanceTo](distance-to.html)(target: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>open fun [distanceTo](distance-to.html)(target: DeviceUID): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the distance between two nodes, through [getDistanceBetweenNodes](../../it.unibo.alchemist.model.interfaces/-environment/get-distance-between-nodes.html). |
| [equals](equals.html) | [jvm]<br>open fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getCoordinates](get-coordinates.html) | [jvm]<br>open fun [getCoordinates](get-coordinates.html)(): Tuple |
| [getCurrentTime](get-current-time.html) | [jvm]<br>open fun [getCurrentTime](get-current-time.html)(): [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html) |
| [getDeltaTime](index.html#323610300%2FFunctions%2F-134779887) | [jvm]<br>open fun [getDeltaTime](index.html#323610300%2FFunctions%2F-134779887)(): [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html) |
| [getDevicePosition](get-device-position.html) | [jvm]<br>open fun [getDevicePosition](get-device-position.html)(): [P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)<br>the device position, in form of [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) |
| [getDeviceUID](get-device-u-i-d.html) | [jvm]<br>open fun [getDeviceUID](get-device-u-i-d.html)(): DeviceUID |
| [getEnvironmentAccess](get-environment-access.html) | [jvm]<br>open fun [getEnvironmentAccess](get-environment-access.html)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)><br>experimental access to the simulated environment, for building oracles |
| [getExecutionEnvironment](index.html#820522942%2FFunctions%2F-134779887) | [jvm]<br>fun [getExecutionEnvironment](index.html#820522942%2FFunctions%2F-134779887)(): ExecutionEnvironment |
| [getPersistent](index.html#1845817213%2FFunctions%2F-134779887) | [jvm]<br>fun <[S](index.html#1845817213%2FFunctions%2F-134779887)> [getPersistent](index.html#1845817213%2FFunctions%2F-134779887)(ifAbsent: [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[S](index.html#1845817213%2FFunctions%2F-134779887)>): [S](index.html#1845817213%2FFunctions%2F-134779887) |
| [getStoredState](index.html#-2085107245%2FFunctions%2F-134779887) | [jvm]<br>fun [getStoredState](index.html#-2085107245%2FFunctions%2F-134779887)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<CodePath, [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [getVariable](index.html#357308502%2FFunctions%2F-134779887) | [jvm]<br>fun [getVariable](index.html#357308502%2FFunctions%2F-134779887)(name: Reference): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [hashCode](hash-code.html) | [jvm]<br>open fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [nbrDelay](nbr-delay.html) | [jvm]<br>open fun [nbrDelay](nbr-delay.html)(): Field<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)><br>The same behavior of MIT Proto's nbrdelay (forward view). |
| [nbrLag](nbr-lag.html) | [jvm]<br>open fun [nbrLag](nbr-lag.html)(): Field<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
| [nbrRange](nbr-range.html) | [jvm]<br>open fun [nbrRange](nbr-range.html)(): Field<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
| [nbrVector](nbr-vector.html) | [jvm]<br>open fun [nbrVector](nbr-vector.html)(): Field<Tuple> |
| [newCallStackFrame](index.html#-1810580144%2FFunctions%2F-134779887) | [jvm]<br>fun [newCallStackFrame](index.html#-1810580144%2FFunctions%2F-134779887)(id: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>) |
| [nextRandomDouble](next-random-double.html) | [jvm]<br>open fun [nextRandomDouble](next-random-double.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [putMultipleVariables](index.html#-1832710005%2FFunctions%2F-134779887) | [jvm]<br>fun [putMultipleVariables](index.html#-1832710005%2FFunctions%2F-134779887)(map: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<Reference, out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [putVariable](index.html#-2122810385%2FFunctions%2F-134779887) | [jvm]<br>fun [putVariable](index.html#-2122810385%2FFunctions%2F-134779887)(name: Reference, value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) |
| [restrictDomain](index.html#-89206816%2FFunctions%2F-134779887) | [jvm]<br>fun [restrictDomain](index.html#-89206816%2FFunctions%2F-134779887)(f: Field<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [S](index.html#1845817213%2FFunctions%2F-134779887)<br>abstract fun [restrictDomain](index.html#1459682554%2FFunctions%2F-134779887)(p: Field<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): ExecutionContext |
| [returnFromCallFrame](index.html#1240485818%2FFunctions%2F-134779887) | [jvm]<br>fun [returnFromCallFrame](index.html#1240485818%2FFunctions%2F-134779887)() |
| [routingDistance](routing-distance.html) | [jvm]<br>open fun [routingDistance](routing-distance.html)(dest: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>open fun [routingDistance](routing-distance.html)(dest: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>open fun [routingDistance](routing-distance.html)(dest: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>open fun [routingDistance](routing-distance.html)(dest: Tuple): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the distance along a map. |
| [runInNewStackFrame](index.html#-22757318%2FFunctions%2F-134779887) | [jvm]<br>fun <[T](index.html#-22757318%2FFunctions%2F-134779887)> [runInNewStackFrame](index.html#-22757318%2FFunctions%2F-134779887)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), operation: (ExecutionContext) -> [T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)): [T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html) |
| [setGloballyAvailableReferences](index.html#-361806%2FFunctions%2F-134779887) | [jvm]<br>fun [setGloballyAvailableReferences](index.html#-361806%2FFunctions%2F-134779887)(knownFunctions: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<Reference, out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [setPersistent](index.html#415770115%2FFunctions%2F-134779887) | [jvm]<br>fun [setPersistent](index.html#415770115%2FFunctions%2F-134779887)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) |
| [setup](index.html#-1430719598%2FFunctions%2F-134779887) | [jvm]<br>fun [setup](index.html#-1430719598%2FFunctions%2F-134779887)() |


## Properties


| Name | Summary |
|---|---|
| [APPROXIMATE_NBR_RANGE](-a-p-p-r-o-x-i-m-a-t-e_-n-b-r_-r-a-n-g-e.html) | [jvm]<br>val [APPROXIMATE_NBR_RANGE](-a-p-p-r-o-x-i-m-a-t-e_-n-b-r_-r-a-n-g-e.html): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)<br>Put this [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html) inside nodes that should compute distances using routes approximating them. |
| [randomGenerator](random-generator.html) | [jvm]<br>private val [randomGenerator](random-generator.html): RandomGenerator |
| [USE_ROUTES_AS_DISTANCES](-u-s-e_-r-o-u-t-e-s_-a-s_-d-i-s-t-a-n-c-e-s.html) | [jvm]<br>val [USE_ROUTES_AS_DISTANCES](-u-s-e_-r-o-u-t-e-s_-a-s_-d-i-s-t-a-n-c-e-s.html): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)<br>Put this [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html) inside nodes that should compute distances using routes. |

