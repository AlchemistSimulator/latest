//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.md)/[AngleManagerImpl](index.md)

# AngleManagerImpl

[jvm]\
class [AngleManagerImpl](index.md) : [AbstractSlideInputManager](../-abstract-slide-input-manager/index.md), [AngleManager](../../it.unibo.alchemist.boundary.wormhole.interfaces/-angle-manager/index.md)

An AngleManager converts the sliding of any physical/virtual device/control into an angle expressed with radians.

## Constructors

| | |
|---|---|
| [AngleManagerImpl](-angle-manager-impl.md) | [jvm]<br>open fun [AngleManagerImpl](-angle-manager-impl.md)()<br>Initializes a new AngleManager instance with dUnit = 1 and dPhase = 0. |
| [AngleManagerImpl](-angle-manager-impl.md) | [jvm]<br>open fun [AngleManagerImpl](-angle-manager-impl.md)(dUnit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Initializes a new AngleManager instance with dPhase = 0. |
| [AngleManagerImpl](-angle-manager-impl.md) | [jvm]<br>open fun [AngleManagerImpl](-angle-manager-impl.md)(dUnit: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), dPhase: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Initializes a new AngleManager with the initial phase and unit in input. |

## Functions

| Name | Summary |
|---|---|
| [dec](../-abstract-slide-input-manager/dec.md) | [jvm]<br>fun [dec](../-abstract-slide-input-manager/dec.md)(val: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [getAngle](get-angle.md) | [jvm]<br>open fun [getAngle](get-angle.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [inc](../-abstract-slide-input-manager/inc.md) | [jvm]<br>fun [inc](../-abstract-slide-input-manager/inc.md)(val: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [DEF_DEG_PER_PIXEL](-d-e-f_-d-e-g_-p-e-r_-p-i-x-e-l.md) | [jvm]<br>val [DEF_DEG_PER_PIXEL](-d-e-f_-d-e-g_-p-e-r_-p-i-x-e-l.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>DEF_DEG_PER_PIXEL = "DEFault amount of DEGrees PER PIXEL". |
