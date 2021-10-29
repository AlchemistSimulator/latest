---
title: ChemotacticPolarization
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[ChemotacticPolarization](index.html)/[ChemotacticPolarization](-chemotactic-polarization.html)



# ChemotacticPolarization



[jvm]\
open fun [ChemotacticPolarization](-chemotactic-polarization.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.html)>, node: [CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.html)<[P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.html)>, biomolecule: [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.html), ascendGrad: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| biomolecule | biomolecule's name |
| ascendGrad | if that parameter is true, the polarization versor of the cell will be directed in direction of the highest concentration of biomolecule in neighborhood; if it's false, the versor will be directed in the exactly the opposite direction. |





[jvm]\
open fun [ChemotacticPolarization](-chemotactic-polarization.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, biomolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), ascendGrad: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))



Initialize a polarization activity regulated by environmental concentration of a molecule.



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| biomolecule | biomolecule's name |
| ascendGrad | if that parameter is true, the polarization versor of the cell will be directed in direction of the highest concentration of biomolecule in neighborhood; if it's false, the versor will be directed in the exactly the opposite direction. |




