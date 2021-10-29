//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.interfaces](../index.md)/[DrawCommand](index.md)/[wrap](wrap.md)

# wrap

[jvm]\
open fun [wrap](wrap.md)(booleanSupplier: [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)>): [DrawCommand](index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)>

Wrapper method that wraps this [DrawCommand](index.md) into another that checks if should execute or not the [accept](accept.md) method.

#### Return

a new [DrawCommand](index.md) that wraps this one around the if checking

## Parameters

jvm

| | |
|---|---|
| booleanSupplier | a condition checker [Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)[Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html) |
