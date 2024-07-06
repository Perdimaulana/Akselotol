---
author: JimSeaman42
ms.author: mikeam
title: Block Documentation - run_command
description: "A reference document detailing the 'run_command' block event response"
ms.service: minecraft-bedrock-edition
---

# Block Documentation - run_command

`run_command` is an event response that will trigger a slash command or a series of slash commands set in an array.

## Extra Parameters

`run_command` can use the following parameters

|Name |Default Value  |Type  |Description  |
|:----------|:----------|:----------|:----------|
|command|*not set* |String|  Slash command to run. |
|command array|*not set* | Array|  List of slash commands to run. |
|[target](../../../EntityReference/Examples/FilterList.md)| self| Minecraft Filter|  The target context to execute against. |

## Example

```json
"run_command":{
    "command" : "/give @p emerald",
    "command array": [], //not used
    "target" : "self"
}
```
