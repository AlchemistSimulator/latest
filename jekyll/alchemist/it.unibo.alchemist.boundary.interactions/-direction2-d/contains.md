---
title: contains
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.interactions](../index.html)/[Direction2D](index.html)/[contains](contains.html)



# contains



[jvm]\
operator fun [contains](contains.html)(other: [Direction2D](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)



Returns whether this direction contains [other](contains.html). Specifically, a direction "D" contains another if D [Direction2D.plus](contains.html) equals D. For example, [NORTHEAST](-n-o-r-t-h-e-a-s-t/index.html) contains [NORTH](-n-o-r-t-h/index.html) and [EAST](-e-a-s-t/index.html), but not [WEST](-w-e-s-t/index.html). All directions contain [NONE](-n-o-n-e/index.html). [NONE](-n-o-n-e/index.html) contains only [NONE](-n-o-n-e/index.html).




