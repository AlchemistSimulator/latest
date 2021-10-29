//[alchemist](../../../index.md)/[it.unibo.alchemist.protelis](../index.md)/[AlchemistExecutionContext](index.md)

# AlchemistExecutionContext

[jvm]\
class [AlchemistExecutionContext](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>?> : AbstractExecutionContext<[AlchemistExecutionContext](index.md)<[P](index.md)>> , SpatiallyEmbeddedDevice<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> , LocalizedDevice, TimeAwareDevice

## Parameters

jvm

| | |
|---|---|
| <P> | position type |

## Constructors

| | |
|---|---|
| [AlchemistExecutionContext](-alchemist-execution-context.md) | [jvm]<br>open fun [AlchemistExecutionContext](-alchemist-execution-context.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](index.md)>, localNode: [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.md)<[P](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, random: RandomGenerator, networkManager: [AlchemistNetworkManager](../-alchemist-network-manager/index.md))<br>the simulation [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md) |

## Functions

| Name | Summary |
|---|---|
| [buildField](index.md#1729644764%2FFunctions%2F-267951372) | [jvm]<br>fun <[T](index.md#1729644764%2FFunctions%2F-267951372), [R](index.md#1729644764%2FFunctions%2F-267951372)> [buildField](index.md#1729644764%2FFunctions%2F-267951372)(computeValue: ([T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.md)) -> [R](index.md#1729644764%2FFunctions%2F-267951372), localValue: [T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.md)): Field<[R](index.md#1729644764%2FFunctions%2F-267951372)> |
| [buildFieldDeferred](index.md#819827614%2FFunctions%2F-267951372) | [jvm]<br>fun <[T](index.md#819827614%2FFunctions%2F-267951372), [R](index.md#819827614%2FFunctions%2F-267951372)> [buildFieldDeferred](index.md#819827614%2FFunctions%2F-267951372)(computeValue: ([T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.md)) -> [R](index.md#1729644764%2FFunctions%2F-267951372), currentLocal: [T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.md), toBeSent: [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.md)>): Field<[R](index.md#1729644764%2FFunctions%2F-267951372)> |
| [commit](index.md#-1965213452%2FFunctions%2F-267951372) | [jvm]<br>fun [commit](index.md#-1965213452%2FFunctions%2F-267951372)() |
| [distanceTo](distance-to.md) | [jvm]<br>open fun [distanceTo](distance-to.md)(target: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>open fun [distanceTo](distance-to.md)(target: DeviceUID): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the distance between two nodes, through [getDistanceBetweenNodes](../../it.unibo.alchemist.model.interfaces/-environment/get-distance-between-nodes.md). |
| [equals](equals.md) | [jvm]<br>open fun [equals](equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getCoordinates](get-coordinates.md) | [jvm]<br>open fun [getCoordinates](get-coordinates.md)(): Tuple |
| [getCurrentTime](get-current-time.md) | [jvm]<br>open fun [getCurrentTime](get-current-time.md)(): [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html) |
| [getDeltaTime](index.md#323610300%2FFunctions%2F-267951372) | [jvm]<br>open fun [getDeltaTime](index.md#323610300%2FFunctions%2F-267951372)(): [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html) |
| [getDevicePosition](get-device-position.md) | [jvm]<br>open fun [getDevicePosition](get-device-position.md)(): [P](index.md)<br>the device position, in form of [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) |
| [getDeviceUID](get-device-u-i-d.md) | [jvm]<br>open fun [getDeviceUID](get-device-u-i-d.md)(): DeviceUID |
| [getEnvironmentAccess](get-environment-access.md) | [jvm]<br>open fun [getEnvironmentAccess](get-environment-access.md)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](index.md)><br>experimental access to the simulated environment, for building oracles |
| [getExecutionEnvironment](index.md#820522942%2FFunctions%2F-267951372) | [jvm]<br>fun [getExecutionEnvironment](index.md#820522942%2FFunctions%2F-267951372)(): ExecutionEnvironment |
| [getPersistent](index.md#1845817213%2FFunctions%2F-267951372) | [jvm]<br>fun <[S](index.md#1845817213%2FFunctions%2F-267951372)> [getPersistent](index.md#1845817213%2FFunctions%2F-267951372)(ifAbsent: [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[S](index.md#1845817213%2FFunctions%2F-267951372)>): [S](index.md#1845817213%2FFunctions%2F-267951372) |
| [getStoredState](index.md#-2085107245%2FFunctions%2F-267951372) | [jvm]<br>fun [getStoredState](index.md#-2085107245%2FFunctions%2F-267951372)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<CodePath, [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [getVariable](index.md#357308502%2FFunctions%2F-267951372) | [jvm]<br>fun [getVariable](index.md#357308502%2FFunctions%2F-267951372)(name: Reference): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [hashCode](hash-code.md) | [jvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [nbrDelay](nbr-delay.md) | [jvm]<br>open fun [nbrDelay](nbr-delay.md)(): Field<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)><br>The same behavior of MIT Proto's nbrdelay (forward view). |
| [nbrLag](nbr-lag.md) | [jvm]<br>open fun [nbrLag](nbr-lag.md)(): Field<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
| [nbrRange](nbr-range.md) | [jvm]<br>open fun [nbrRange](nbr-range.md)(): Field<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
| [nbrVector](nbr-vector.md) | [jvm]<br>open fun [nbrVector](nbr-vector.md)(): Field<Tuple> |
| [newCallStackFrame](index.md#-1810580144%2FFunctions%2F-267951372) | [jvm]<br>fun [newCallStackFrame](index.md#-1810580144%2FFunctions%2F-267951372)(id: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>) |
| [nextRandomDouble](next-random-double.md) | [jvm]<br>open fun [nextRandomDouble](next-random-double.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [putMultipleVariables](index.md#-1832710005%2FFunctions%2F-267951372) | [jvm]<br>fun [putMultipleVariables](index.md#-1832710005%2FFunctions%2F-267951372)(map: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<Reference, out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [putVariable](index.md#-2122810385%2FFunctions%2F-267951372) | [jvm]<br>fun [putVariable](index.md#-2122810385%2FFunctions%2F-267951372)(name: Reference, value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) |
| [restrictDomain](index.md#-89206816%2FFunctions%2F-267951372) | [jvm]<br>fun [restrictDomain](index.md#-89206816%2FFunctions%2F-267951372)(f: Field<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [S](index.md#1845817213%2FFunctions%2F-267951372)<br>abstract fun [restrictDomain](index.md#1459682554%2FFunctions%2F-267951372)(p: Field<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): ExecutionContext |
| [returnFromCallFrame](index.md#1240485818%2FFunctions%2F-267951372) | [jvm]<br>fun [returnFromCallFrame](index.md#1240485818%2FFunctions%2F-267951372)() |
| [routingDistance](routing-distance.md) | [jvm]<br>open fun [routingDistance](routing-distance.md)(dest: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>open fun [routingDistance](routing-distance.md)(dest: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>open fun [routingDistance](routing-distance.md)(dest: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>open fun [routingDistance](routing-distance.md)(dest: Tuple): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the distance along a map. |
| [runInNewStackFrame](index.md#-22757318%2FFunctions%2F-267951372) | [jvm]<br>fun <[T](index.md#-22757318%2FFunctions%2F-267951372)> [runInNewStackFrame](index.md#-22757318%2FFunctions%2F-267951372)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), operation: (ExecutionContext) -> [T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.md)): [T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.md) |
| [setGloballyAvailableReferences](index.md#-361806%2FFunctions%2F-267951372) | [jvm]<br>fun [setGloballyAvailableReferences](index.md#-361806%2FFunctions%2F-267951372)(knownFunctions: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<Reference, out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [setPersistent](index.md#415770115%2FFunctions%2F-267951372) | [jvm]<br>fun [setPersistent](index.md#415770115%2FFunctions%2F-267951372)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) |
| [setup](index.md#-1430719598%2FFunctions%2F-267951372) | [jvm]<br>fun [setup](index.md#-1430719598%2FFunctions%2F-267951372)() |

## Properties

| Name | Summary |
|---|---|
| [APPROXIMATE_NBR_RANGE](-a-p-p-r-o-x-i-m-a-t-e_-n-b-r_-r-a-n-g-e.md) | [jvm]<br>val [APPROXIMATE_NBR_RANGE](-a-p-p-r-o-x-i-m-a-t-e_-n-b-r_-r-a-n-g-e.md): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)<br>Put this [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md) inside nodes that should compute distances using routes approximating them. |
| [randomGenerator](random-generator.md) | [jvm]<br>private val [randomGenerator](random-generator.md): RandomGenerator |
| [USE_ROUTES_AS_DISTANCES](-u-s-e_-r-o-u-t-e-s_-a-s_-d-i-s-t-a-n-c-e-s.md) | [jvm]<br>val [USE_ROUTES_AS_DISTANCES](-u-s-e_-r-o-u-t-e-s_-a-s_-d-i-s-t-a-n-c-e-s.md): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)<br>Put this [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md) inside nodes that should compute distances using routes. |
