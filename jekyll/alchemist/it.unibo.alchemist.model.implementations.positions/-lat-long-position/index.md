---
title: LatLongPosition
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.positions](../index.html)/[LatLongPosition](index.html)



# LatLongPosition



[jvm]\
class [LatLongPosition](index.html) : [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)

Unmodifiable state version of LatLng, also implementing the [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html) interface.



## Constructors


| | |
|---|---|
| [LatLongPosition](-lat-long-position.html) | [jvm]<br>open fun [LatLongPosition](-lat-long-position.html)(lat: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), lon: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>latitude |
| [LatLongPosition](-lat-long-position.html) | [jvm]<br>open fun [LatLongPosition](-lat-long-position.html)(lat: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), lon: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), distanceFormula: [LatLongPosition.DistanceFormula](-distance-formula/index.html))<br>latitude |
| [LatLongPosition](-lat-long-position.html) | [jvm]<br>open fun [LatLongPosition](-lat-long-position.html)(lat: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), lon: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), distanceFormula: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>latitude |
| [LatLongPosition](-lat-long-position.html) | [jvm]<br>open fun [LatLongPosition](-lat-long-position.html)(lat: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), lon: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html))<br>latitude |


## Types


| Name | Summary |
|---|---|
| [DistanceFormula](-distance-formula/index.html) | [jvm]<br>enum [DistanceFormula](-distance-formula/index.html)<br>Possible methods to compute the distance between two latitude-longitude points. |


## Functions


| Name | Summary |
|---|---|
| [boundingBox](bounding-box.html) | [jvm]<br>open fun [boundingBox](bounding-box.html)(range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> |
| [distance](distance.html) | [jvm]<br>open fun [distance](distance.html)(point1: LatLng, point2: LatLng, df: [LatLongPosition.DistanceFormula](-distance-formula/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Distance between two points.<br>[jvm]<br>open fun [distance](distance.html)(point1: LatLng, point2: LatLng, unit: LengthUnit, df: [LatLongPosition.DistanceFormula](-distance-formula/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Distance between two points with arbitrary LengthUnit. |
| [distanceInRadians](distance-in-radians.html) | [jvm]<br>open fun [distanceInRadians](distance-in-radians.html)(point1: LatLng, point2: LatLng, precision: [LatLongPosition.DistanceFormula](-distance-formula/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br> This "distance" function is mostly for internal use. |
| [distanceTo](distance-to.html) | [jvm]<br>open fun [distanceTo](distance-to.html)(@NotNull()otherPosition: @NotNull()[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [equals](equals.html) | [jvm]<br>open fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getCoordinate](get-coordinate.html) | [jvm]<br>open fun [getCoordinate](get-coordinate.html)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCoordinates](get-coordinates.html) | [jvm]<br>open fun [getCoordinates](get-coordinates.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getDimensions](get-dimensions.html) | [jvm]<br>open fun [getDimensions](get-dimensions.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getLatitude](get-latitude.html) | [jvm]<br>open fun [getLatitude](get-latitude.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the latitude |
| [getLongitude](get-longitude.html) | [jvm]<br>open fun [getLongitude](get-longitude.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the longitude |
| [getX](get-x.html) | [jvm]<br>open fun [getX](get-x.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getY](get-y.html) | [jvm]<br>open fun [getY](get-y.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [hashCode](hash-code.html) | [jvm]<br>open fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [minus](minus.html) | [jvm]<br>@NotNull()<br>open fun [minus](minus.html)(@NotNull()other: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): @NotNull()[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)<br>open fun [minus](minus.html)(@NotNull()other: @NotNull()[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html) |
| [plus](plus.html) | [jvm]<br>@NotNull()<br>open fun [plus](plus.html)(@NotNull()other: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): @NotNull()[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)<br>open fun [plus](plus.html)(@NotNull()other: @NotNull()[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html) |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Properties


| Name | Summary |
|---|---|
| [DEFAULT_DISTANCE_FORMULA](-d-e-f-a-u-l-t_-d-i-s-t-a-n-c-e_-f-o-r-m-u-l-a.html) | [jvm]<br>val [DEFAULT_DISTANCE_FORMULA](-d-e-f-a-u-l-t_-d-i-s-t-a-n-c-e_-f-o-r-m-u-l-a.html): [LatLongPosition.DistanceFormula](-distance-formula/index.html)<br>The default distance formula. |
| [EARTH_MEAN_RADIUS_METERS](-e-a-r-t-h_-m-e-a-n_-r-a-d-i-u-s_-m-e-t-e-r-s.html) | [jvm]<br>val [EARTH_MEAN_RADIUS_METERS](-e-a-r-t-h_-m-e-a-n_-r-a-d-i-u-s_-m-e-t-e-r-s.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Mean Earth radius in meters. |

