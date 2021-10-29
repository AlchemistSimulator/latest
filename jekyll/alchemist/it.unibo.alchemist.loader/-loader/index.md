---
title: Loader
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader](../index.html)/[Loader](index.html)



# Loader



[jvm]\
interface [Loader](index.html) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

An entity which is able to produce an Alchemist [InitializedEnvironment](../-initialized-environment/index.html), resolving user defined variable values.



## Functions


| Name | Summary |
|---|---|
| [getConstants](get-constants.html) | [jvm]<br>abstract fun [getConstants](get-constants.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>Allows to access the currently defined constants, namely variables defined in the simulation file whose value is constant and does not depend on the value of any free variable (directly or indirectly). |
| [getDefault](get-default.html) | [jvm]<br>open fun <[T](get-default.html), [P](get-default.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.loader.shapes/-circle/index.html)>?> [getDefault](get-default.html)(): [InitializedEnvironment](../-initialized-environment/index.html)<[T](../../it.unibo.alchemist.loader.deployments/-deployment/get-associated-linking-rule.html), [P](../../it.unibo.alchemist.loader.shapes/-circle/index.html)><br>concentration type |
| [getDependentVariables](get-dependent-variables.html) | [jvm]<br>abstract fun [getDependentVariables](get-dependent-variables.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [DependentVariable](../../it.unibo.alchemist.loader.variables/-dependent-variable/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>><br>Allows to access the currently defined dependent variable (those variables whose value can be determined given a valid set of values for the free variables). |
| [getRemoteDependencies](get-remote-dependencies.html) | [jvm]<br>abstract fun [getRemoteDependencies](get-remote-dependencies.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)><br>dependencies files |
| [getVariables](get-variables.html) | [jvm]<br>abstract fun [getVariables](get-variables.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [Variable](../../it.unibo.alchemist.loader.variables/-variable/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>><br>a [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html) between variable names and their actual representation |
| [getWith](get-with.html) | [jvm]<br>abstract fun <[T](get-with.html), [P](get-with.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.loader.shapes/-circle/index.html)>?> [getWith](get-with.html)(values: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [InitializedEnvironment](../-initialized-environment/index.html)<[T](../../it.unibo.alchemist.loader.deployments/-deployment/get-associated-linking-rule.html), [P](../../it.unibo.alchemist.loader.shapes/-circle/index.html)><br>a map specifying name-value bindings for the variables in this scenario |

