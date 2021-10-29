---
title: GeometricGradientRectangle
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.deployments](../index.html)/[GeometricGradientRectangle](index.html)/[GeometricGradientRectangle](-geometric-gradient-rectangle.html)



# GeometricGradientRectangle



[jvm]\
open fun [GeometricGradientRectangle](-geometric-gradient-rectangle.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.loader.shapes/-circle/index.html)>, rng: RandomGenerator, nodes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sizex: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sizey: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), lambda: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), steps: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), horizontal: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), increasing: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))



Use this constructor to displace multiple groups of devices with exponentially varied density along an axis.



## Parameters


jvm

| | |
|---|---|
| env | [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html) |
| rng | RandomGenerator |
| nodes | the number of nodes to displace |
| x | start x position |
| y | start y position |
| sizex | width |
| sizey | height |
| lambda | the lambda parameter of the exponential. The actual lambda is computed by multiplying this value with the dimension chosen for the exponential distribution |
| steps | number of discrete groups. One falls back to uniform distribution, very large values approximate a continuous exponential distribution |
| horizontal | true if the exponential axis is horizontal |
| increasing | true if device density should increase with the desired axis |





[jvm]\
open fun [GeometricGradientRectangle](-geometric-gradient-rectangle.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.loader.shapes/-circle/index.html)>, rng: RandomGenerator, nodes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sizex: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sizey: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), lambda: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), horizontal: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), increasing: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))



Use this constructor to displace devices with an exponentially varied density along an axis.



## Parameters


jvm

| | |
|---|---|
| env | [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html) |
| rng | RandomGenerator |
| nodes | the number of nodes to displace |
| x | start x position |
| y | start y position |
| sizex | width |
| sizey | height |
| lambda | the lambda parameter of the exponential. The actual lambda is computed by multiplying this value with the dimension chosen for the exponential distribution |
| horizontal | true if the exponential axis is horizontal |
| increasing | true if device density should increase with the desired axis |




