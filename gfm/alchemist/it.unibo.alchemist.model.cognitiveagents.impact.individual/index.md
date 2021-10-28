//[alchemist](../../index.md)/[it.unibo.alchemist.model.cognitiveagents.impact.individual](index.md)

# Package it.unibo.alchemist.model.cognitiveagents.impact.individual

## Types

| Name | Summary |
|---|---|
| [Age](-age/index.md) | [jvm]<br>enum [Age](-age/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Age](-age/index.md)> , [Characteristic](-characteristic/index.md)<br>An enum representing the different periods of life. |
| [Characteristic](-characteristic/index.md) | [jvm]<br>interface [Characteristic](-characteristic/index.md)<br>Any characteristic associated to a pedestrian. |
| [Compliance](-compliance/index.md) | [jvm]<br>class [Compliance](-compliance/index.md)(**age**: [Age](-age/index.md), **gender**: [Gender](-gender/index.md)) : [Characteristic](-characteristic/index.md)<br>The level of compliance of an agent considering its gender and its age. |
| [ComplianceSpec](-compliance-spec/index.md) | [jvm]<br>object [ComplianceSpec](-compliance-spec/index.md) : ConfigSpec<br>A specification of the parameters regarding compliance to load from a config file. |
| [Gender](-gender/index.md) | [jvm]<br>enum [Gender](-gender/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Gender](-gender/index.md)> , [Characteristic](-characteristic/index.md)<br>An enum representing the different genders. |
| [HelpAttitude](-help-attitude/index.md) | [jvm]<br>class [HelpAttitude](-help-attitude/index.md)(**age**: [Age](-age/index.md), **gender**: [Gender](-gender/index.md)) : [Characteristic](-characteristic/index.md)<br>The attitude of an agent towards helping another agent. |
| [HelpAttitudeSpec](-help-attitude-spec/index.md) | [jvm]<br>object [HelpAttitudeSpec](-help-attitude-spec/index.md) : ConfigSpec<br>A specification of the parameters regarding help attitudes to load from a config file. |
| [Speed](-speed/index.md) | [jvm]<br>class [Speed](-speed/index.md)(**age**: [Age](-age/index.md), **gender**: [Gender](-gender/index.md), **rg**: RandomGenerator) : [Characteristic](-characteristic/index.md)<br>The speed of an agent considering its age, gender and a random factor. |
| [SpeedSpec](-speed-spec/index.md) | [jvm]<br>object [SpeedSpec](-speed-spec/index.md) : ConfigSpec<br>A specification of the parameters regarding speeds to load from a config file. |
