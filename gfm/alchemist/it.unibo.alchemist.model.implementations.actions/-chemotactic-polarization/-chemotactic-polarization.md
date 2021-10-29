//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[ChemotacticPolarization](index.md)/[ChemotacticPolarization](-chemotactic-polarization.md)

# ChemotacticPolarization

[jvm]\
open fun [ChemotacticPolarization](-chemotactic-polarization.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model.implementations.environments/-abstract2-d-environment/index.md)>, node: [CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.md)<[P](../../it.unibo.alchemist.model.implementations.environments/-abstract2-d-environment/index.md)>, biomolecule: [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.md), ascendGrad: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))

## Parameters

jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| biomolecule | biomolecule's name |
| ascendGrad | if that parameter is true, the polarization versor of the cell will be directed in direction of the highest concentration of biomolecule in neighborhood; if it's false, the versor will be directed in the exactly the opposite direction. |

[jvm]\
open fun [ChemotacticPolarization](-chemotactic-polarization.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model.implementations.environments/-abstract2-d-environment/index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, biomolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), ascendGrad: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))

Initialize a polarization activity regulated by environmental concentration of a molecule.

## Parameters

jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| biomolecule | biomolecule's name |
| ascendGrad | if that parameter is true, the polarization versor of the cell will be directed in direction of the highest concentration of biomolecule in neighborhood; if it's false, the versor will be directed in the exactly the opposite direction. |
