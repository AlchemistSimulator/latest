---
title: next
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[EnvironmentWithObstacles](index.html)/[next](next.html)



# next



[jvm]\
abstract fun [next](next.html)(current: [P](index.html), desired: [P](index.html)): [P](index.html)



This method must calculate the ABSOLUTE next allowed position given the current position and the position in which the node wants to move. For example, if your node is in position 2,3, wants to move to 3,4 but the next allowed position (because, e.g., of physical obstacles) is 2.5,3.5, the result must be a Position containing coordinates 2.5,3.5.



#### Return



the next allowed position, where the node can actually move. This position MUST be considered as a vector whose start point is [current](next.html).



## Parameters


jvm

| | |
|---|---|
| current | the current position |
| desired | the desired position |



