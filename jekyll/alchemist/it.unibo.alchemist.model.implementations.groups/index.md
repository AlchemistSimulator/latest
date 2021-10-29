---
title: it.unibo.alchemist.model.implementations.groups
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.implementations.groups](index.html)



# Package it.unibo.alchemist.model.implementations.groups



## Types


| Name | Summary |
|---|---|
| [Alone](-alone/index.html) | [jvm]<br>class [Alone](-alone/index.html)<[T](-alone/index.html), [S](-alone/index.html) : [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[S](-alone/index.html)>, [A](-alone/index.html) : [GeometricTransformation](../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[S](-alone/index.html)>>(**pedestrian**: [Pedestrian](../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](-alone/index.html), [S](-alone/index.html), [A](-alone/index.html)>) : [PedestrianGroup](../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html)<[T](-alone/index.html), [S](-alone/index.html), [A](-alone/index.html)> <br>Group representing a pedestrian alone. |
| [Family](-family/index.html) | [jvm]<br>class [Family](-family/index.html)<[T](-family/index.html), [S](-family/index.html) : [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[S](-family/index.html)>, [A](-family/index.html) : [GeometricTransformation](../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[S](-family/index.html)>>(**comparator**: [Comparator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparator/index.html)<[Pedestrian](../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](-family/index.html), [S](-family/index.html), [A](-family/index.html)>>) : [GenericGroup](-generic-group/index.html)<[T](-family/index.html), [Pedestrian](../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](-family/index.html), [S](-family/index.html), [A](-family/index.html)>> , [GroupWithLeader](../it.unibo.alchemist.model.interfaces/-group-with-leader/index.html)<[T](-family/index.html), [Pedestrian](../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](-family/index.html), [S](-family/index.html), [A](-family/index.html)>> <br>A [Family](-family/index.html) is modeled as a group of pedestrians with a leader. |
| [Friends](-friends/index.html) | [jvm]<br>class [Friends](-friends/index.html)<[T](-friends/index.html), [S](-friends/index.html) : [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[S](-friends/index.html)>, [A](-friends/index.html) : [GeometricTransformation](../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[S](-friends/index.html)>> : [GenericGroup](-generic-group/index.html)<[T](-friends/index.html), [Pedestrian](../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](-friends/index.html), [S](-friends/index.html), [A](-friends/index.html)>> <br>A generic, leaderless group of pedestrians. |
| [GenericGroup](-generic-group/index.html) | [jvm]<br>open class [GenericGroup](-generic-group/index.html)<[T](-generic-group/index.html), [N](-generic-group/index.html) : [Node](../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](-generic-group/index.html)>> : [Group](../it.unibo.alchemist.model.interfaces/-group/index.html)<[T](-generic-group/index.html), [N](-generic-group/index.html)> <br>Basic implementation of a group. |
| [GroupFactory](-group-factory/index.html) | [jvm]<br>object [GroupFactory](-group-factory/index.html)<br>Utility for shorter loading of groups within the Yaml files. |

