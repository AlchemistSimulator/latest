---
title: LinearZoomManager
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.html)/[LinearZoomManager](index.html)/[LinearZoomManager](-linear-zoom-manager.html)



# LinearZoomManager



[jvm]\
open fun [LinearZoomManager](-linear-zoom-manager.html)(z: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))



Same of [LinearZoomManager](-linear-zoom-manager.html) but rate is 1, and minimum and maximum are +/- [MAX_VALUE](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html#MAX_VALUE--).



## Parameters


jvm

| | |
|---|---|
| z | is the desired initial zoom |





[jvm]\
open fun [LinearZoomManager](-linear-zoom-manager.html)(zoom: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), rate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), min: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), max: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))



Initialize a new [LinearZoomManager](index.html) instance with the parameters in input.



## Parameters


jvm

| | |
|---|---|
| zoom | is the desired initial zoom |
| rate | is the linear factor |
| min | minimum allowed zoom |
| max | maximum allowed zoom |




