---
author: mammerla
ms.author: mikeam
title: Block Documentation - minecraft:on_player_placing
description: "A reference document detailing the 'on_player_placing' block trigger"
ms.service: minecraft-bedrock-edition
---

# Block Documentation - minecraft:on_player_placing

`minecraft:on_player_placing` is an Event Trigger for when an actor, that is tagged as a player, places a block in the world.

## Parameters

`minecraft:on_player_placing` can use the following parameters

|Name |Default Value  |Type  |Description  |
|:----------|:----------|:----------|:----------|
|condition|*not set* | String|  The condition of event to be executed on the block. |
|event|*not set* | String|  The event executed on the block. |
| target| self| String| The target of event executed on the block. |

## Example

```json
"minecraft:on_player_placing":{
    "condition": "query.block_state(custom:state) == true", //custom condition
    "event" : "i_put_the_block_down", //custom event
    "target": "self"
}
```
