---
title: AngleManagerImpl
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.html)/[AngleManagerImpl](index.html)



# AngleManagerImpl



[jvm]\
class [AngleManagerImpl](index.html) : [AbstractSlideInputManager](../-abstract-slide-input-manager/index.html), [AngleManager](../../it.unibo.alchemist.boundary.wormhole.interfaces/-angle-manager/index.html)

An AngleManager converts the sliding of any physical/virtual device/control into an angle expressed with radians.



## Constructors


| | |
|---|---|
| [AngleManagerImpl](-angle-manager-impl.html) | [jvm]<br>open fun [AngleManagerImpl](-angle-manager-impl.html)()<br>Initializes a new AngleManager instance with dUnit = 1 and dPhase = 0. |
| [AngleManagerImpl](-angle-manager-impl.html) | [jvm]<br>open fun [AngleManagerImpl](-angle-manager-impl.html)(dUnit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Initializes a new AngleManager instance with dPhase = 0. |
| [AngleManagerImpl](-angle-manager-impl.html) | [jvm]<br>open fun [AngleManagerImpl](-angle-manager-impl.html)(dUnit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), dPhase: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Initializes a new AngleManager with the initial phase and unit in input. |


## Functions


| Name | Summary |
|---|---|
| [dec](../-abstract-slide-input-manager/dec.html) | [jvm]<br>fun [dec](../-abstract-slide-input-manager/dec.html)(val: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [getAngle](get-angle.html) | [jvm]<br>open fun [getAngle](get-angle.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [inc](../-abstract-slide-input-manager/inc.html) | [jvm]<br>fun [inc](../-abstract-slide-input-manager/inc.html)(val: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [DEF_DEG_PER_PIXEL](-d-e-f_-d-e-g_-p-e-r_-p-i-x-e-l.html) | [jvm]<br>val [DEF_DEG_PER_PIXEL](-d-e-f_-d-e-g_-p-e-r_-p-i-x-e-l.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>DEF_DEG_PER_PIXEL = "DEFault amount of DEGrees PER PIXEL". |

