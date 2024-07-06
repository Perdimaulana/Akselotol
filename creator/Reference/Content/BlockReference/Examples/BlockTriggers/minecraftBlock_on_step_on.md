---
author: mammerla
ms.author: mikeam
title: Block Documentation - minecraft:on_step_on
description: "A reference document detailing the 'on_step_on' block trigger"
ms.service: minecraft-bedrock-edition
---

# Block Documentation - minecraft:on_step_on

`minecraft:on_step_on` is an Event Trigger for when an entity steps on the block.

## Parameters

`minecraft:on_step_on` can use the following parameters

|Name |Default Value  |Type  |Description  |
|:----------|:----------|:----------|:----------|
|condition|*not set* | String|  The condition of event to be executed on the block. |
|event|*not set* | String|  The event executed on the block. |
| target| self| String| The target of event executed on the block. |

## Example

```json
"minecraft:on_step_on":{
    "condition": "query.block_state(custom:is_playing_sound) == false", //custom condition
    "event" : "sound_the_alarm", //custom event
    "target": "self"
}
```
