//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.view.properties](../index.md)/[PropertyFactory](index.md)/[getAWTColorChannelProperty](get-a-w-t-color-channel-property.md)

# getAWTColorChannelProperty

[jvm]\
open fun [getAWTColorChannelProperty](get-a-w-t-color-channel-property.md)(channel: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [RangedIntegerProperty](../-ranged-integer-property/index.md)

Returns a new [RangedIntegerProperty](../-ranged-integer-property/index.md) with range between 255 and 0 and a name that identifies the color channel.

#### Return

the [RangedIntegerProperty](../-ranged-integer-property/index.md)

## Parameters

jvm

| | |
|---|---|
| channel | the name to give to the {@code Property} |

[jvm]\
open fun [getAWTColorChannelProperty](get-a-w-t-color-channel-property.md)(channel: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), value: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [RangedIntegerProperty](../-ranged-integer-property/index.md)

Returns a new [RangedIntegerProperty](../-ranged-integer-property/index.md) with range between 255 and 0 and a name that identifies the color channel.

#### Return

the javafx.beans.property.IntegerProperty

## Parameters

jvm

| | |
|---|---|
| channel | the name to give to the {@code Property} |
| value | the initial value to give to the {@code Property} |
