//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.view.properties](../index.md)/[RangedIntegerProperty](index.md)/[RangedIntegerProperty](-ranged-integer-property.md)

# RangedIntegerProperty

[jvm]\
open fun [RangedIntegerProperty](-ranged-integer-property.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), initialValue: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), lowerBound: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), upperBound: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Based on constructor of IntegerPropertyBase, adds the specified bounds.

## Parameters

jvm

| | |
|---|---|
| name | the name of this {@code IntegerProperty} |
| initialValue | the initial value of the wrapped value |
| lowerBound | the lower bound for the wrapped value to be considered acceptable |
| upperBound | the upper bound for the wrapped value to be considered acceptable |

[jvm]\
open fun [RangedIntegerProperty](-ranged-integer-property.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), lowerBound: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), upperBound: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Based on constructor of IntegerPropertyBase, adds the specified bounds. 

 Initial value is set to 0.

## Parameters

jvm

| | |
|---|---|
| name | the name of this {@code IntegerProperty} |
| lowerBound | the lower bound for the wrapped value to be considered acceptable |
| upperBound | the upper bound for the wrapped value to be considered acceptable |

[jvm]\
open fun [RangedIntegerProperty](-ranged-integer-property.md)(initialValue: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), lowerBound: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), upperBound: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Based on constructor of IntegerPropertyBase, adds the specified bounds.

## Parameters

jvm

| | |
|---|---|
| initialValue | the initial value of the wrapped value |
| lowerBound | the lower bound for the wrapped value to be considered acceptable |
| upperBound | the upper bound for the wrapped value to be considered acceptable |

[jvm]\
open fun [RangedIntegerProperty](-ranged-integer-property.md)(lowerBound: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), upperBound: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Based on constructor of IntegerPropertyBase, adds the specified bounds. 

 Initial value is set to 0.

## Parameters

jvm

| | |
|---|---|
| lowerBound | the lower bound for the wrapped value to be considered acceptable |
| upperBound | the upper bound for the wrapped value to be considered acceptable |

[jvm]\
open fun [RangedIntegerProperty](-ranged-integer-property.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), initialValue: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

The constructor of IntegerPropertyBase. 

 Bounds are set to [MAX_VALUE](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html#MAX_VALUE--) and [MIN_VALUE](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html#MIN_VALUE--).

## Parameters

jvm

| | |
|---|---|
| name | the name of this {@code IntegerProperty} |
| initialValue | the initial value of the wrapped value |

[jvm]\
open fun [RangedIntegerProperty](-ranged-integer-property.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))

The constructor of IntegerPropertyBase. 

 Initial value is set to 0. 

 Bounds are set to [MAX_VALUE](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html#MAX_VALUE--) and [MIN_VALUE](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html#MIN_VALUE--).

## Parameters

jvm

| | |
|---|---|
| name | the name of this {@code IntegerProperty} |

[jvm]\
open fun [RangedIntegerProperty](-ranged-integer-property.md)(initialValue: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

The constructor of IntegerPropertyBase. 

 Bounds are set to [MAX_VALUE](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html#MAX_VALUE--) and [MIN_VALUE](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html#MIN_VALUE--).

## Parameters

jvm

| | |
|---|---|
| initialValue | the initial value of the wrapped value |

[jvm]\
open fun [RangedIntegerProperty](-ranged-integer-property.md)()

The constructor of IntegerPropertyBase. 

 Initial value is set to 0. 

 Bounds are set to [MAX_VALUE](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html#MAX_VALUE--) and [MIN_VALUE](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html#MIN_VALUE--).
