//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.layers](../index.md)/[BiomolGradientLayer](index.md)/[getParameters](get-parameters.md)

# getParameters

[jvm]\
open fun [getParameters](get-parameters.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>

#### Return

the parameters describing this spatial distribution, that's actually a plain. So the [java.lang.reflect.Array](https://docs.oracle.com/javase/8/docs/api/java/lang/reflect/Array.html) a returned by this method contains the parameters of that plain (concentration = a[0] * x + a[1] * y + a[2])