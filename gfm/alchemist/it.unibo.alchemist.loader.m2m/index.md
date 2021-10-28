//[alchemist](../../index.md)/[it.unibo.alchemist.loader.m2m](index.md)

# Package it.unibo.alchemist.loader.m2m

## Types

| Name | Summary |
|---|---|
| [JVMConstructor](-j-v-m-constructor/index.md) | [jvm]<br>sealed class [JVMConstructor](-j-v-m-constructor/index.md)<br>A constructor for a JVM class of type [typeName](-j-v-m-constructor/type-name.md). |
| [NamedParametersConstructor](-named-parameters-constructor/index.md) | [jvm]<br>class [NamedParametersConstructor](-named-parameters-constructor/index.md)(**type**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **parametersMap**: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<*, *>) : [JVMConstructor](-j-v-m-constructor/index.md)<br>A [JVMConstructor](-j-v-m-constructor/index.md) whose parameters are named and hence stored in a parametersMap (no pure Java class works with named parameters now, Kotlin-only). |
| [OrderedParametersConstructor](-ordered-parameters-constructor/index.md) | [jvm]<br>class [OrderedParametersConstructor](-ordered-parameters-constructor/index.md)(**type**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **parameters**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<*>) : [JVMConstructor](-j-v-m-constructor/index.md)<br>A [JVMConstructor](-j-v-m-constructor/index.md) whose parameters are an ordered list (common case for any JVM language). |
