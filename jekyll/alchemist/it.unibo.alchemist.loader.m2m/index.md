---
title: it.unibo.alchemist.loader.m2m
---
//[alchemist](../../index.html)/[it.unibo.alchemist.loader.m2m](index.html)



# Package it.unibo.alchemist.loader.m2m



## Types


| Name | Summary |
|---|---|
| [JVMConstructor](-j-v-m-constructor/index.html) | [jvm]<br>sealed class [JVMConstructor](-j-v-m-constructor/index.html)<br>A constructor for a JVM class of type [typeName](-j-v-m-constructor/type-name.html). |
| [NamedParametersConstructor](-named-parameters-constructor/index.html) | [jvm]<br>class [NamedParametersConstructor](-named-parameters-constructor/index.html)(**type**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **parametersMap**: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<*, *>) : [JVMConstructor](-j-v-m-constructor/index.html)<br>A [JVMConstructor](-j-v-m-constructor/index.html) whose parameters are named and hence stored in a parametersMap (no pure Java class works with named parameters now, Kotlin-only). |
| [OrderedParametersConstructor](-ordered-parameters-constructor/index.html) | [jvm]<br>class [OrderedParametersConstructor](-ordered-parameters-constructor/index.html)(**type**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **parameters**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<*>) : [JVMConstructor](-j-v-m-constructor/index.html)<br>A [JVMConstructor](-j-v-m-constructor/index.html) whose parameters are an ordered list (common case for any JVM language). |

