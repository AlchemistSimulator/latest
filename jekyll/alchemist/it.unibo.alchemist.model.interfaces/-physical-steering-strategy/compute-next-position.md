---
title: computeNextPosition
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[PhysicalSteeringStrategy](index.html)/[computeNextPosition](compute-next-position.html)



# computeNextPosition



[jvm]\
abstract fun [computeNextPosition](compute-next-position.html)(overallIntentionalForce: [P](index.html)): [P](index.html)



Computes the next relative position reached by the node, given the overall intentional force.





[jvm]\
open override fun [computeNextPosition](compute-next-position.html)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../-steering-action/index.html)<[T](index.html), [P](index.html)>>): [P](index.html)



Computes the next relative position reached by the node, taking into account both the intentional and the physical forces acting on [node](node.html) (intentional forces = [actions](compute-next-position.html)).




