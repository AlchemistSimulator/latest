//[alchemist](../../index.md)/[it.unibo.alchemist.boundary](index.md)

# Package it.unibo.alchemist.boundary

## Types

| Name | Summary |
|---|---|
| [CustomLeafletMapView](-custom-leaflet-map-view/index.md) | [jvm]<br>class [CustomLeafletMapView](-custom-leaflet-map-view/index.md) : LeafletMapView<br>A LeafletMapView that implements functions used to manage the map without any mouse events. |
| [EditKeybindView](-edit-keybind-view/index.md) | [jvm]<br>class [EditKeybindView](-edit-keybind-view/index.md) : View<br>The view through which keybinds can be edited. |
| [Keybind](-keybind/index.md) | [jvm]<br>class [Keybind](-keybind/index.md)(**action**: [ActionFromKey](../it.unibo.alchemist.input/-action-from-key/index.md), **key**: KeyCode)<br>A class that describes the relation between a KeyCode and an Action. |
| [KeybindController](-keybind-controller/index.md) | [jvm]<br>class [KeybindController](-keybind-controller/index.md) : Controller<br>The controller for ListKeybindsView. |
| [Keybinder](-keybinder/index.md) | [jvm]<br>class [Keybinder](-keybinder/index.md) : App<br>The keybinder app. |
| [KeybindModel](-keybind-model/index.md) | [jvm]<br>class [KeybindModel](-keybind-model/index.md) : ItemViewModel<[Keybind](-keybind/index.md)> <br>The ItemViewModel of a Keybind. |
| [ListKeybindsView](-list-keybinds-view/index.md) | [jvm]<br>class [ListKeybindsView](-list-keybinds-view/index.md) : View<br>The view that lists current keybinds. |

## Functions

| Name | Summary |
|---|---|
| [clear](clear.md) | [jvm]<br>fun Canvas.[clear](clear.md)()<br>Clears a given canvas. |
| [contains](contains.md) | [jvm]<br>operator fun Rectangle.[contains](contains.md)(point: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns whether the Rectangle contains [point](contains.md). |
| [createDrawRectangleCommand](create-draw-rectangle-command.md) | [jvm]<br>fun Canvas.[createDrawRectangleCommand](create-draw-rectangle-command.md)(rectangle: Rectangle, colour: Paint): () -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Returns a command for drawing the given rectangle on the caller canvas. |
| [intersectingNodes](intersecting-nodes.md) | [jvm]<br>fun <[T](intersecting-nodes.md), [P](intersecting-nodes.md) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](intersecting-nodes.md)>> Rectangle.[intersectingNodes](intersecting-nodes.md)(nodes: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Node](../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](intersecting-nodes.md)>, [P](intersecting-nodes.md)>, wormhole: [Wormhole2D](../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](intersecting-nodes.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Node](../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](intersecting-nodes.md)>, [P](intersecting-nodes.md)><br>Returns the nodes intersecting with the caller rectangle. |
| [makePoint](make-point.md) | [jvm]<br>fun [makePoint](make-point.md)(x: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), y: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Creates a [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html). |
| [makeRectangleWith](make-rectangle-with.md) | [jvm]<br>fun [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html).[makeRectangleWith](make-rectangle-with.md)(other: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): Rectangle<br>Creates a rectangle that has this and [other](make-rectangle-with.md) as its opposite-diagonal vertexes. |
| [minus](minus.md) | [jvm]<br>operator fun [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html).[minus](minus.md)(p: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Subtracts this and the given [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html). |
| [plus](plus.md) | [jvm]<br>operator fun [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html).[plus](plus.md)(p: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Sums this and the given [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html). |
