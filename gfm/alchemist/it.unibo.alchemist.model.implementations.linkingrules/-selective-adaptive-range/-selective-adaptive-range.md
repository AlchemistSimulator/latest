//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.linkingrules](../index.md)/[SelectiveAdaptiveRange](index.md)/[SelectiveAdaptiveRange](-selective-adaptive-range.md)

# SelectiveAdaptiveRange

[jvm]\
open fun [SelectiveAdaptiveRange](-selective-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

## Parameters

jvm

| | |
|---|---|
| radius | default radius in metres |
| minrange | minimum radius in metres |
| maxrange | maximum radius in metres |
| desiredNeighborsCount | preferred number of neighbors |
| tolerance | if the number of neighbors is smaller than num-tolerance, the radius is increased; if the number of neighbors is higher than num+tolerance, the radius is decreased |

[jvm]\
open fun [SelectiveAdaptiveRange](-selective-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), adjustment: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Parameters

jvm

| | |
|---|---|
| radius | default radius in metres |
| minrange | minimum radius in metres |
| maxrange | maximum radius in metres |
| desiredNeighborsCount | preferred number of neighbors |
| tolerance | if the number of neighbors is smaller than desiredNeighborsCount-tolerance, the radius is increased; if the number of neighbors is higher than desiredNeighborsCount+tolerance, the radius is decreased |
| adjustment | the amount of metres the range will be changed if out of the bounds |

[jvm]\
open fun [SelectiveAdaptiveRange](-selective-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), adjustment: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), molType: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))

## Parameters

jvm

| | |
|---|---|
| radius | default radius in metres |
| minrange | minimum radius in metres |
| maxrange | maximum radius in metres |
| desiredNeighborsCount | preferred number of neighbors |
| tolerance | if the number of neighbors is smaller than desiredNeighborsCount-tolerance, the radius is increased; if the number of neighbors is higher than desiredNeighborsCount+tolerance, the radius is decreased |
| adjustment | the amount of metres the range will be changed if out of the bounds |
| molType | the molecule whose presence will allow links to be created |

[jvm]\
open fun [SelectiveAdaptiveRange](-selective-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

## Parameters

jvm

| | |
|---|---|
| radius | default radius in metres |
| minrange | minimum radius in metres |
| desiredNeighborsCount | preferred number of neighbors |
| tolerance | if the number of neighbors is smaller than desiredNeighborsCount-tolerance, the radius is increased; if the number of neighbors is higher than desiredNeighborsCount+tolerance, the radius is decreased |

[jvm]\
open fun [SelectiveAdaptiveRange](-selective-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), adjustment: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Parameters

jvm

| | |
|---|---|
| radius | default radius in metres |
| minrange | minimum radius in metres |
| desiredNeighborsCount | preferred number of neighbors |
| tolerance | if the number of neighbors is smaller than desiredNeighborsCount-tolerance, the radius is increased; if the number of neighbors is higher than desiredNeighborsCount+tolerance, the radius is decreased |
| adjustment | the amount of metres the range will be changed if out of the bounds |

[jvm]\
open fun [SelectiveAdaptiveRange](-selective-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

## Parameters

jvm

| | |
|---|---|
| radius | default radius in metres |
| desiredNeighborsCount | preferred number of neighbors |
| tolerance | if the number of neighbors is smaller than desiredNeighborsCount-tolerance, the radius is increased; if the number of neighbors is higher than desiredNeighborsCount+tolerance, the radius is decreased |

[jvm]\
open fun [SelectiveAdaptiveRange](-selective-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), adjustment: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Parameters

jvm

| | |
|---|---|
| radius | default radius in metres |
| desiredNeighborsCount | preferred number of neighbors |
| tolerance | if the number of neighbors is smaller than desiredNeighborsCount-tolerance, the radius is increased; if the number of neighbors is higher than desiredNeighborsCount+tolerance, the radius is decreased |
| adjustment | the amount of metres the range will be changed if out of the bounds |

[jvm]\
open fun [SelectiveAdaptiveRange](-selective-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), molType: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))

## Parameters

jvm

| | |
|---|---|
| radius | default radius in metres |
| desiredNeighborsCount | preferred number of neighbors |
| tolerance | if the number of neighbors is smaller than desiredNeighborsCount-tolerance, the radius is increased; if the number of neighbors is higher than desiredNeighborsCount+tolerance, the radius is decreased |
| molType | the molecule whose presence will allow links to be created |
