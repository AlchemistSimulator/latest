---
title: it.unibo.alchemist.model.cognitiveagents.impact.individual
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.cognitiveagents.impact.individual](index.html)



# Package it.unibo.alchemist.model.cognitiveagents.impact.individual



## Types


| Name | Summary |
|---|---|
| [Age](-age/index.html) | [jvm]<br>enum [Age](-age/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Age](-age/index.html)> , [Characteristic](-characteristic/index.html)<br>An enum representing the different periods of life. |
| [Characteristic](-characteristic/index.html) | [jvm]<br>interface [Characteristic](-characteristic/index.html)<br>Any characteristic associated to a pedestrian. |
| [Compliance](-compliance/index.html) | [jvm]<br>class [Compliance](-compliance/index.html)(**age**: [Age](-age/index.html), **gender**: [Gender](-gender/index.html)) : [Characteristic](-characteristic/index.html)<br>The level of compliance of an agent considering its gender and its age. |
| [ComplianceSpec](-compliance-spec/index.html) | [jvm]<br>object [ComplianceSpec](-compliance-spec/index.html) : ConfigSpec<br>A specification of the parameters regarding compliance to load from a config file. |
| [Gender](-gender/index.html) | [jvm]<br>enum [Gender](-gender/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Gender](-gender/index.html)> , [Characteristic](-characteristic/index.html)<br>An enum representing the different genders. |
| [HelpAttitude](-help-attitude/index.html) | [jvm]<br>class [HelpAttitude](-help-attitude/index.html)(**age**: [Age](-age/index.html), **gender**: [Gender](-gender/index.html)) : [Characteristic](-characteristic/index.html)<br>The attitude of an agent towards helping another agent. |
| [HelpAttitudeSpec](-help-attitude-spec/index.html) | [jvm]<br>object [HelpAttitudeSpec](-help-attitude-spec/index.html) : ConfigSpec<br>A specification of the parameters regarding help attitudes to load from a config file. |
| [Speed](-speed/index.html) | [jvm]<br>class [Speed](-speed/index.html)(**age**: [Age](-age/index.html), **gender**: [Gender](-gender/index.html), **rg**: RandomGenerator) : [Characteristic](-characteristic/index.html)<br>The speed of an agent considering its age, gender and a random factor. |
| [SpeedSpec](-speed-spec/index.html) | [jvm]<br>object [SpeedSpec](-speed-spec/index.html) : ConfigSpec<br>A specification of the parameters regarding speeds to load from a config file. |

