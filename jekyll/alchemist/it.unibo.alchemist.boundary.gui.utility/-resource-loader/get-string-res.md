---
title: getStringRes
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.utility](../index.html)/[ResourceLoader](index.html)/[getStringRes](get-string-res.html)



# getStringRes



[jvm]\
open fun [getStringRes](get-string-res.html)(key: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)



Looks up on the property files and returns the correct String.



#### Return



the string



## Parameters


jvm

| | |
|---|---|
| key | the key |



#### Throws


| | |
|---|---|
| [java.lang.NullPointerException](https://docs.oracle.com/javase/8/docs/api/java/lang/NullPointerException.html) | if key is null |
| [java.util.MissingResourceException](https://docs.oracle.com/javase/8/docs/api/java/util/MissingResourceException.html) | if no object for the given key or no resource bundle can be found |
| [java.lang.ClassCastException](https://docs.oracle.com/javase/8/docs/api/java/lang/ClassCastException.html) | if the object found for the given key is not a string |




[jvm]\
open fun [getStringRes](get-string-res.html)(key: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), locale: [Locale](https://docs.oracle.com/javase/8/docs/api/java/util/Locale.html)): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)



Looks up on the property files and returns the correct String.



#### Return



the string



## Parameters


jvm

| | |
|---|---|
| key | the key |
| locale | the locale |



#### Throws


| | |
|---|---|
| [java.lang.NullPointerException](https://docs.oracle.com/javase/8/docs/api/java/lang/NullPointerException.html) | if key or locale is null |
| [java.util.MissingResourceException](https://docs.oracle.com/javase/8/docs/api/java/util/MissingResourceException.html) | if no object for the given key or no resource bundle can be found |
| [java.lang.ClassCastException](https://docs.oracle.com/javase/8/docs/api/java/lang/ClassCastException.html) | if the object found for the given key is not a string |



