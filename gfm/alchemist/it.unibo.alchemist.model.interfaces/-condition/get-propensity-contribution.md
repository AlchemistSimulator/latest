//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Condition](index.md)/[getPropensityContribution](get-propensity-contribution.md)

# getPropensityContribution

[jvm]\
abstract fun [getPropensityContribution](get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)

This method is a support for the propensity calculation inside the Reactions. It allows this condition to influence the rate calculation in some way. It's up to the reaction to decide whether to use or not this information, and how.

#### Return

how this condition may influence the propensity.
