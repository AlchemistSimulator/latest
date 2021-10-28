//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.interactions](../index.md)/[Direction2D](index.md)/[contains](contains.md)

# contains

[jvm]\
operator fun [contains](contains.md)(other: [Direction2D](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Returns whether this direction contains [other](contains.md). Specifically, a direction "D" contains another if D [Direction2D.plus](contains.md) equals D. For example, [NORTHEAST](-n-o-r-t-h-e-a-s-t/index.md) contains [NORTH](-n-o-r-t-h/index.md) and [EAST](-e-a-s-t/index.md), but not [WEST](-w-e-s-t/index.md). All directions contain [NONE](-n-o-n-e/index.md). [NONE](-n-o-n-e/index.md) contains only [NONE](-n-o-n-e/index.md).
