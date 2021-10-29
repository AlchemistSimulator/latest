//[alchemist](../../../index.md)/[it.unibo.alchemist.loader](../index.md)/[Loader](index.md)

# Loader

[jvm]\
interface [Loader](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

An entity which is able to produce an Alchemist [InitializedEnvironment](../-initialized-environment/index.md), resolving user defined variable values.

## Functions

| Name | Summary |
|---|---|
| [getConstants](get-constants.md) | [jvm]<br>abstract fun [getConstants](get-constants.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>Allows to access the currently defined constants, namely variables defined in the simulation file whose value is constant and does not depend on the value of any free variable (directly or indirectly). |
| [getDefault](get-default.md) | [jvm]<br>open fun <[T](get-default.md), [P](get-default.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)>?> [getDefault](get-default.md)(): [InitializedEnvironment](../-initialized-environment/index.md)<[T](../../it.unibo.alchemist.loader.deployments/-deployment/get-associated-linking-rule.md), [P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)><br>concentration type |
| [getDependentVariables](get-dependent-variables.md) | [jvm]<br>abstract fun [getDependentVariables](get-dependent-variables.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [DependentVariable](../../it.unibo.alchemist.loader.variables/-dependent-variable/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>><br>Allows to access the currently defined dependent variable (those variables whose value can be determined given a valid set of values for the free variables). |
| [getRemoteDependencies](get-remote-dependencies.md) | [jvm]<br>abstract fun [getRemoteDependencies](get-remote-dependencies.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)><br>dependencies files |
| [getVariables](get-variables.md) | [jvm]<br>abstract fun [getVariables](get-variables.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [Variable](../../it.unibo.alchemist.loader.variables/-variable/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>><br>a [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html) between variable names and their actual representation |
| [getWith](get-with.md) | [jvm]<br>abstract fun <[T](get-with.md), [P](get-with.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)>?> [getWith](get-with.md)(values: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [InitializedEnvironment](../-initialized-environment/index.md)<[T](../../it.unibo.alchemist.loader.deployments/-deployment/get-associated-linking-rule.md), [P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)><br>a map specifying name-value bindings for the variables in this scenario |
