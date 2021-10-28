---
title: SAPERELocalAgent
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[SAPERELocalAgent](index.html)/[SAPERELocalAgent](-s-a-p-e-r-e-local-agent.html)



# SAPERELocalAgent



[jvm]\
open fun [SAPERELocalAgent](-s-a-p-e-r-e-local-agent.html)(node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html))



Creates a new SAPERE Local Agent stub. If you use this constructor, you must be sure that your agent does not modify any molecule (e.g. an agent that just moves a node).



## Parameters


jvm

| | |
|---|---|
| node | The node in which this agent stays |





[jvm]\
open fun [SAPERELocalAgent](-s-a-p-e-r-e-local-agent.html)(node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), m1: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html))



Creates a new SAPERE Agent stub. If you use this constructor, you must be sure that your agent only modifies molecules matching the template passed as m1.



## Parameters


jvm

| | |
|---|---|
| node | The node in which this agent stays |
| m1 | The molecule template it modifies |





[jvm]\
open fun [SAPERELocalAgent](-s-a-p-e-r-e-local-agent.html)(node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), m1: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html), m2: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html))



Creates a new SAPERE Agent stub. If you use this constructor, you must be sure that your agent only modifies molecules matching the template passed as m1 and/or the template passed in m2.



## Parameters


jvm

| | |
|---|---|
| node | The node in which this agent stays |
| m1 | The first molecule template it modifies |
| m2 | The second molecule template it modifies |





[jvm]\
open fun [SAPERELocalAgent](-s-a-p-e-r-e-local-agent.html)(node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), m1: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html), m2: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html), m3: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html))



Creates a new SAPERE Agent stub. If you use this constructor, you must be sure that your agent only modifies molecules matching the template passed as m1 and/or the template passed in m2 and/or the template passed in m3.



## Parameters


jvm

| | |
|---|---|
| node | The node in which this agent stays |
| m1 | The first molecule template it modifies |
| m2 | The second molecule template it modifies |
| m3 | The third molecule template it modifies |




