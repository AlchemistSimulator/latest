---
title: loadScaledImage
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui](../index.html)/[AlchemistSwingUI](index.html)/[loadScaledImage](load-scaled-image.html)



# loadScaledImage



[jvm]\
open fun [loadScaledImage](load-scaled-image.html)(p: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [ImageIcon](https://docs.oracle.com/javase/8/docs/api/javax/swing/ImageIcon.html)



Loads an image and scales it to the default Alchemist's icon size.



#### Return



the resized icon



## Parameters


jvm

| | |
|---|---|
| p | the path where to load the image. The system resource loader is used to do so, with all its advantages |





[jvm]\
open fun [loadScaledImage](load-scaled-image.html)(p: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [ImageIcon](https://docs.oracle.com/javase/8/docs/api/javax/swing/ImageIcon.html)



Loads an image and scales it to the desired size.



#### Return



the resized icon



## Parameters


jvm

| | |
|---|---|
| p | the path where to load the image. The system resource loader is used to do so, with all its advantages |
| size | the size which will be used both for x and y axes |




