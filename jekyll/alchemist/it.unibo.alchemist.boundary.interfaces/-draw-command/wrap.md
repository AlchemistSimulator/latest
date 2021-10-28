---
title: wrap
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.interfaces](../index.html)/[DrawCommand](index.html)/[wrap](wrap.html)



# wrap



[jvm]\
open fun [wrap](wrap.html)(booleanSupplier: [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)>): [DrawCommand](index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>



Wrapper method that wraps this [DrawCommand](index.html) into another that checks if should execute or not the [accept](accept.html) method.



#### Return



a new [DrawCommand](index.html) that wraps this one around the if checking



## Parameters


jvm

| | |
|---|---|
| booleanSupplier | a condition checker [Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)[Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html) |




