//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.molecules](../index.md)/[Junction](index.md)/[Junction](-junction.md)

# Junction

[jvm]\
open fun [Junction](-junction.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), moleculesInCurrentNode: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Biomolecule](../-biomolecule/index.md), [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, moleculesInNeighborNode: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Biomolecule](../-biomolecule/index.md), [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>)

Build a junction.

## Parameters

jvm

| | |
|---|---|
| name | the name of the junction. |
| moleculesInCurrentNode | A map of molecules (with their concentration) which was in the current node. When the junction is removed the molecules will be released in the current node. |
| moleculesInNeighborNode | A map of molecules (with their concentration) which was in the current node. When the junction is removed the molecules will be released in the current node. |

[jvm]\
open fun [Junction](-junction.md)(toClone: [Junction](index.md))

Builds a junction from another junction.

## Parameters

jvm

| | |
|---|---|
| toClone | the junction to clone. |
