---
title: outboundDependencies
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.interfaces](../index.html)/[DependencyGraph](index.html)/[outboundDependencies](outbound-dependencies.html)



# outboundDependencies



[jvm]\
abstract fun [outboundDependencies](outbound-dependencies.html)(reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>): ListSet<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>>



Returns the set of reactions that may be influenced by the provided reaction.



#### Return



the set of reactions that may be influenced by the provided reaction



## Parameters


jvm

| | |
|---|---|
| reaction | the input reaction |




