//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.view](../index.md)/[SingleRunApp](index.md)/[addParam](add-param.md)

# addParam

[jvm]\
open fun [addParam](add-param.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), value: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))

The method adds a new named parameter.

## See also

jvm

| | |
|---|---|
| javafx.application.Application.Parameters | Parameters#getNamed() |

## Parameters

jvm

| | |
|---|---|
| name | the param name |
| value | the param value |

#### Throws

| | |
|---|---|
| [java.lang.IllegalArgumentException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalArgumentException.html) | if the parameter is not valid, or if getUnnamed it's not named} |
| [java.lang.IllegalStateException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalStateException.html) | if the application is already started |
