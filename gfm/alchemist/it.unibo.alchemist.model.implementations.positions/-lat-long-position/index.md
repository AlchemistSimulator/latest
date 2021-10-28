//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.positions](../index.md)/[LatLongPosition](index.md)

# LatLongPosition

[jvm]\
class [LatLongPosition](index.md) : [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)

Unmodifiable state version of LatLng, also implementing the [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md) interface.

## Constructors

| | |
|---|---|
| [LatLongPosition](-lat-long-position.md) | [jvm]<br>open fun [LatLongPosition](-lat-long-position.md)(lat: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), lon: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>latitude |
| [LatLongPosition](-lat-long-position.md) | [jvm]<br>open fun [LatLongPosition](-lat-long-position.md)(lat: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), lon: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), distanceFormula: [LatLongPosition.DistanceFormula](-distance-formula/index.md))<br>latitude |
| [LatLongPosition](-lat-long-position.md) | [jvm]<br>open fun [LatLongPosition](-lat-long-position.md)(lat: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), lon: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), distanceFormula: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>latitude |
| [LatLongPosition](-lat-long-position.md) | [jvm]<br>open fun [LatLongPosition](-lat-long-position.md)(lat: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), lon: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html))<br>latitude |

## Types

| Name | Summary |
|---|---|
| [DistanceFormula](-distance-formula/index.md) | [jvm]<br>enum [DistanceFormula](-distance-formula/index.md)<br>Possible methods to compute the distance between two latitude-longitude points. |

## Functions

| Name | Summary |
|---|---|
| [boundingBox](bounding-box.md) | [jvm]<br>open fun [boundingBox](bounding-box.md)(range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> |
| [distance](distance.md) | [jvm]<br>open fun [distance](distance.md)(point1: LatLng, point2: LatLng, df: [LatLongPosition.DistanceFormula](-distance-formula/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Distance between two points.<br>[jvm]<br>open fun [distance](distance.md)(point1: LatLng, point2: LatLng, unit: LengthUnit, df: [LatLongPosition.DistanceFormula](-distance-formula/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Distance between two points with arbitrary LengthUnit. |
| [distanceInRadians](distance-in-radians.md) | [jvm]<br>open fun [distanceInRadians](distance-in-radians.md)(point1: LatLng, point2: LatLng, precision: [LatLongPosition.DistanceFormula](-distance-formula/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br> This "distance" function is mostly for internal use. |
| [distanceTo](distance-to.md) | [jvm]<br>open fun [distanceTo](distance-to.md)(@NotNull()otherPosition: @NotNull()[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [equals](equals.md) | [jvm]<br>open fun [equals](equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getCoordinate](get-coordinate.md) | [jvm]<br>open fun [getCoordinate](get-coordinate.md)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCoordinates](get-coordinates.md) | [jvm]<br>open fun [getCoordinates](get-coordinates.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getDimensions](get-dimensions.md) | [jvm]<br>open fun [getDimensions](get-dimensions.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getLatitude](get-latitude.md) | [jvm]<br>open fun [getLatitude](get-latitude.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the latitude |
| [getLongitude](get-longitude.md) | [jvm]<br>open fun [getLongitude](get-longitude.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the longitude |
| [getX](get-x.md) | [jvm]<br>open fun [getX](get-x.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getY](get-y.md) | [jvm]<br>open fun [getY](get-y.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [hashCode](hash-code.md) | [jvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [minus](minus.md) | [jvm]<br>@NotNull()<br>open fun [minus](minus.md)(@NotNull()other: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): @NotNull()[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)<br>open fun [minus](minus.md)(@NotNull()other: @NotNull()[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)): [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md) |
| [plus](plus.md) | [jvm]<br>@NotNull()<br>open fun [plus](plus.md)(@NotNull()other: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): @NotNull()[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)<br>open fun [plus](plus.md)(@NotNull()other: @NotNull()[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)): [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md) |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Properties

| Name | Summary |
|---|---|
| [DEFAULT_DISTANCE_FORMULA](-d-e-f-a-u-l-t_-d-i-s-t-a-n-c-e_-f-o-r-m-u-l-a.md) | [jvm]<br>val [DEFAULT_DISTANCE_FORMULA](-d-e-f-a-u-l-t_-d-i-s-t-a-n-c-e_-f-o-r-m-u-l-a.md): [LatLongPosition.DistanceFormula](-distance-formula/index.md)<br>The default distance formula. |
| [EARTH_MEAN_RADIUS_METERS](-e-a-r-t-h_-m-e-a-n_-r-a-d-i-u-s_-m-e-t-e-r-s.md) | [jvm]<br>val [EARTH_MEAN_RADIUS_METERS](-e-a-r-t-h_-m-e-a-n_-r-a-d-i-u-s_-m-e-t-e-r-s.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Mean Earth radius in meters. |
