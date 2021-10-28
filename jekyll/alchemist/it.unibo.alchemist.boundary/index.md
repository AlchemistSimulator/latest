---
title: it.unibo.alchemist.boundary
---
//[alchemist](../../index.html)/[it.unibo.alchemist.boundary](index.html)



# Package it.unibo.alchemist.boundary



## Types


| Name | Summary |
|---|---|
| [CustomLeafletMapView](-custom-leaflet-map-view/index.html) | [jvm]<br>class [CustomLeafletMapView](-custom-leaflet-map-view/index.html) : LeafletMapView<br>A LeafletMapView that implements functions used to manage the map without any mouse events. |
| [EditKeybindView](-edit-keybind-view/index.html) | [jvm]<br>class [EditKeybindView](-edit-keybind-view/index.html) : View<br>The view through which keybinds can be edited. |
| [Keybind](-keybind/index.html) | [jvm]<br>class [Keybind](-keybind/index.html)(**action**: [ActionFromKey](../it.unibo.alchemist.input/-action-from-key/index.html), **key**: KeyCode)<br>A class that describes the relation between a KeyCode and an Action. |
| [KeybindController](-keybind-controller/index.html) | [jvm]<br>class [KeybindController](-keybind-controller/index.html) : Controller<br>The controller for ListKeybindsView. |
| [Keybinder](-keybinder/index.html) | [jvm]<br>class [Keybinder](-keybinder/index.html) : App<br>The keybinder app. |
| [KeybindModel](-keybind-model/index.html) | [jvm]<br>class [KeybindModel](-keybind-model/index.html) : ItemViewModel<[Keybind](-keybind/index.html)> <br>The ItemViewModel of a Keybind. |
| [ListKeybindsView](-list-keybinds-view/index.html) | [jvm]<br>class [ListKeybindsView](-list-keybinds-view/index.html) : View<br>The view that lists current keybinds. |


## Functions


| Name | Summary |
|---|---|
| [clear](clear.html) | [jvm]<br>fun Canvas.[clear](clear.html)()<br>Clears a given canvas. |
| [contains](contains.html) | [jvm]<br>operator fun Rectangle.[contains](contains.html)(point: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns whether the Rectangle contains [point](contains.html). |
| [createDrawRectangleCommand](create-draw-rectangle-command.html) | [jvm]<br>fun Canvas.[createDrawRectangleCommand](create-draw-rectangle-command.html)(rectangle: Rectangle, colour: Paint): () -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Returns a command for drawing the given rectangle on the caller canvas. |
| [intersectingNodes](intersecting-nodes.html) | [jvm]<br>fun <[T](intersecting-nodes.html), [P](intersecting-nodes.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](intersecting-nodes.html)>> Rectangle.[intersectingNodes](intersecting-nodes.html)(nodes: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Node](../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](intersecting-nodes.html)>, [P](intersecting-nodes.html)>, wormhole: [Wormhole2D](../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](intersecting-nodes.html)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Node](../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](intersecting-nodes.html)>, [P](intersecting-nodes.html)><br>Returns the nodes intersecting with the caller rectangle. |
| [makePoint](make-point.html) | [jvm]<br>fun [makePoint](make-point.html)(x: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), y: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Creates a [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html). |
| [makeRectangleWith](make-rectangle-with.html) | [jvm]<br>fun [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html).[makeRectangleWith](make-rectangle-with.html)(other: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): Rectangle<br>Creates a rectangle that has this and [other](make-rectangle-with.html) as its opposite-diagonal vertexes. |
| [minus](minus.html) | [jvm]<br>operator fun [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html).[minus](minus.html)(p: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Subtracts this and the given [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html). |
| [plus](plus.html) | [jvm]<br>operator fun [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html).[plus](plus.html)(p: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Sums this and the given [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html). |

