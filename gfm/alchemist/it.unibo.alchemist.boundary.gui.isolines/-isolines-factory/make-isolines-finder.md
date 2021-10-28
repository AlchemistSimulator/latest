//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.isolines](../index.md)/[IsolinesFactory](index.md)/[makeIsolinesFinder](make-isolines-finder.md)

# makeIsolinesFinder

[jvm]\
abstract fun [makeIsolinesFinder](make-isolines-finder.md)(algorithm: [IsolinesFactory.IsolineFinders](-isoline-finders/index.md)): [IsolinesFinder](../-isolines-finder/index.md)

Create an IsolinesFinder object, capable of finding isolines. As different finders could be available - each one extracting isolines in a different way - you can specify which one to use with the algorithm parameter.

#### Return

the IsolineFinder

## Parameters

jvm

| | |
|---|---|
| algorithm | - the algorithm you want to use |
