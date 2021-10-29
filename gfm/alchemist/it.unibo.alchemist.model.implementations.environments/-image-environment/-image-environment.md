//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.environments](../index.md)/[ImageEnvironment](index.md)/[ImageEnvironment](-image-environment.md)

# ImageEnvironment

[jvm]\
open fun [ImageEnvironment](-image-environment.md)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[T](../-continuous2-d-obstacles/index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))

## Parameters

jvm

| | |
|---|---|
| incarnation | the incarnation to be used. |
| path | the path where to load the image. Must be a local file path. |

#### Throws

| | |
|---|---|
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | if image file cannot be found, or if you disconnected your hard drive while this method was running. |

[jvm]\
open fun [ImageEnvironment](-image-environment.md)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[T](../-continuous2-d-obstacles/index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), zoom: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Parameters

jvm

| | |
|---|---|
| incarnation | the incarnation to be used. |
| path | the path where to load the image. Must be a local file path. |
| zoom | zoom level |

#### Throws

| | |
|---|---|
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | if image file cannot be found, or if you disconnected your hard drive while this method was running. |

[jvm]\
open fun [ImageEnvironment](-image-environment.md)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[T](../-continuous2-d-obstacles/index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), zoom: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), dx: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), dy: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Parameters

jvm

| | |
|---|---|
| incarnation | the incarnation to be used. |
| path | the path where to load the image. Must be a local file path. |
| zoom | zoom level |
| dx | delta X position |
| dy | delta Y position |

#### Throws

| | |
|---|---|
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | if image file cannot be found, or if you disconnected your hard drive while this method was running. |

[jvm]\
open fun [ImageEnvironment](-image-environment.md)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[T](../-continuous2-d-obstacles/index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, obstacleColor: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), zoom: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), dx: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), dy: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Parameters

jvm

| | |
|---|---|
| incarnation | the incarnation to be used. |
| obstacleColor | integer representing the RGB color to use as color for the obstacle detection in image. Encoding follows common Java rules: [getRGB](https://docs.oracle.com/javase/8/docs/api/java/awt/Color.html#getRGB--) |
| path | the path where to load the image. Must be a local file path. |
| zoom | zoom level |
| dx | delta X position |
| dy | delta Y position |

#### Throws

| | |
|---|---|
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | if image file cannot be found, or if you disconnected your hard drive while this method was running. |
