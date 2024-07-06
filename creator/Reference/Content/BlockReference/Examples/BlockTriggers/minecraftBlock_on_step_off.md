---
author: mammerla
ms.author: mikeam
title: Block Documentation - minecraft:on_step_off
description: "A reference document detailing the 'on_step_off' block trigger"
ms.service: minecraft-bedrock-edition
---

# Block Documentation - minecraft:on_step_off

`minecraft:on_step_off` is an Event Trigger for when an entity steps off the block.

## Parameters

`minecraft:on_step_off` can use the following parameters

|Name |Default Value  |Type  |Description  |
|:----------|:----------|:----------|:----------|
|condition|*not set* | String|  The condition of event to be executed on the block. |
|event|*not set* | String|  The event executed on the block. |
| target| self| String| The target of event executed on the block. |

## Example

```json
"minecraft:on_step_off":{
    "condition": "query.block_state(custom:is_playing_sound) == true", //custom condition
    "event" : "disable_the_alarm", //custom event
    "target": "self"
}
```
