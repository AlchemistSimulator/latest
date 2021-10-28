//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gpsload.impl](../index.md)/[TraceLoader](index.md)/[TraceLoader](-trace-loader.md)

# TraceLoader

[jvm]\
open fun [TraceLoader](-trace-loader.md)(path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), cycle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), normalizer: [GPSTimeAlignment](../../it.unibo.alchemist.boundary.gpsload.api/-g-p-s-time-alignment/index.md))

## Parameters

jvm

| | |
|---|---|
| path | path with the gps tracks |
| cycle | true if considering list of GPSTrace cycle, default false |
| normalizer | normalizer to use for normalize time |

#### Throws

| | |
|---|---|
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | in case of I/O errors |

[jvm]\
open fun [TraceLoader](-trace-loader.md)(path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), cycle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), timeNormalizerClass: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), normalizerArgs: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)

## Parameters

jvm

| | |
|---|---|
| path | path with the gps tracks |
| cycle | true if considering list of GPSTrace cycle, default false |
| timeNormalizerClass | class to use to normalize time |
| normalizerArgs | args to use to create GPSTimeNormalizer |

#### Throws

| | |
|---|---|
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | in case of I/O errors |

[jvm]\
open fun [TraceLoader](-trace-loader.md)(path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), normalizer: [GPSTimeAlignment](../../it.unibo.alchemist.boundary.gpsload.api/-g-p-s-time-alignment/index.md))

## Parameters

jvm

| | |
|---|---|
| path | path with the gps tracks |
| normalizer | normalizer to use for normalize time |

#### Throws

| | |
|---|---|
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | in case of I/O errors |

[jvm]\
open fun [TraceLoader](-trace-loader.md)(path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), timeNormalizerClass: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), normalizerArgs: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)

## Parameters

jvm

| | |
|---|---|
| path | path with the gps tracks |
| timeNormalizerClass | class to use to normalize time |
| normalizerArgs | args to use to create GPSTimeNormalizer |

#### Throws

| | |
|---|---|
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | in case of I/O errors |
