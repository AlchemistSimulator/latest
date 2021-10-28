---
title: it.unibo.alchemist.boundary.monitors
---
//[alchemist](../../index.html)/[it.unibo.alchemist.boundary.monitors](index.html)



# Package it.unibo.alchemist.boundary.monitors



[jvm]\
This package contains generic monitors for various Environments.



## Types


| Name | Summary |
|---|---|
| [AbstractFXDisplay](-abstract-f-x-display/index.html) | [jvm]<br>abstract class [AbstractFXDisplay](-abstract-f-x-display/index.html)<[T](-abstract-f-x-display/index.html), [P](-abstract-f-x-display/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](-abstract-f-x-display/index.html)>> : Pane, [FXOutputMonitor](../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.html)<[T](-abstract-f-x-display/index.html), [P](-abstract-f-x-display/index.html)> <br>Base abstract class for each display able to graphically represent a 2D space and simulation. |
| [FX2DDisplay](-f-x2-d-display/index.html) | [jvm]<br>class [FX2DDisplay](-f-x2-d-display/index.html)<[T](-f-x2-d-display/index.html), [P](-f-x2-d-display/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](-f-x2-d-display/index.html)>> : [AbstractFXDisplay](-abstract-f-x-display/index.html)<[T](-f-x2-d-display/index.html), [P](-f-x2-d-display/index.html)> <br>Simple implementation of a monitor that graphically represents a 2D space and simulation. |
| [Generic2DDisplay](-generic2-d-display/index.html) | [jvm]<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~open~~ ~~class~~ [~~Generic2DDisplay~~](-generic2-d-display/index.html)~~<~~[T](-generic2-d-display/index.html)~~,~~ [P](-generic2-d-display/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?~~>~~ ~~:~~ [~~JPanel~~](https://docs.oracle.com/javase/8/docs/api/javax/swing/JPanel.html)~~,~~ [~~Graphical2DOutputMonitor~~](../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)~~<~~[~~T~~](../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)~~,~~ [~~P~~](../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)~~>~~ <br>Base-class for each display able a graphically represent a 2D space and simulation. |
| [LeafletMapDisplay](-leaflet-map-display/index.html) | [jvm]<br>class [LeafletMapDisplay](-leaflet-map-display/index.html)<[T](-leaflet-map-display/index.html)> : [AbstractFXDisplay](-abstract-f-x-display/index.html)<[T](-leaflet-map-display/index.html), [GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> <br>Simple implementation of a monitor that graphically represents a simulation on a 2D map, specifically LeafletMap. |
| [MapDisplay](-map-display/index.html) | [jvm]<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~class~~ [~~MapDisplay~~](-map-display/index.html)~~<~~[T](-map-display/index.html)~~>~~ ~~:~~ [~~Generic2DDisplay~~](-generic2-d-display/index.html)~~<~~[~~T~~](../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)~~,~~ [GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.html)~~>~~ <br>Graphical 2D display of an environments that uses a map. |
| [MoleculeInjectorGUI](-molecule-injector-g-u-i/index.html) | [jvm]<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~open~~ ~~class~~ [~~MoleculeInjectorGUI~~](-molecule-injector-g-u-i/index.html)~~<~~[T](-molecule-injector-g-u-i/index.html)~~>~~ ~~:~~ [~~JPanel~~](https://docs.oracle.com/javase/8/docs/api/javax/swing/JPanel.html)<br>This class raises a new JPanel which allows to graphically inject a new molecule inside a node (or a group of nodes) or to modify the value of a certain molecule. |
| [NodeTracker](-node-tracker/index.html) | [jvm]<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~class~~ [~~NodeTracker~~](-node-tracker/index.html)~~<~~[T](-node-tracker/index.html)~~,~~ [P](-node-tracker/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?~~>~~ ~~:~~ [~~JPanel~~](https://docs.oracle.com/javase/8/docs/api/javax/swing/JPanel.html)~~,~~ [~~OutputMonitor~~](../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)~~<~~[~~T~~](../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)~~,~~ [~~P~~](../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)~~>~~ ~~,~~ [~~ActionListener~~](https://docs.oracle.com/javase/8/docs/api/java/awt/event/ActionListener.html)<br>position type |
| [TimeStepMonitor](-time-step-monitor/index.html) | [jvm]<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~class~~ [~~TimeStepMonitor~~](-time-step-monitor/index.html)~~<~~[T](-time-step-monitor/index.html)~~,~~ [P](-time-step-monitor/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?~~>~~ ~~:~~ [~~JPanel~~](https://docs.oracle.com/javase/8/docs/api/javax/swing/JPanel.html)~~,~~ [~~OutputMonitor~~](../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)~~<~~[~~T~~](../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)~~,~~ [~~P~~](../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)~~>~~ <br>position type |
