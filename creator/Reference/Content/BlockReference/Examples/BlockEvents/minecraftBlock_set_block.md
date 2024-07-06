---
author: mammerla
ms.author: mikeam
title: Block Documentation - set_block
description: "A reference document detailing the 'set_block' block event response"
ms.service: minecraft-bedrock-edition
---

# Block Documentation - set_block

`set_block` is an Event Response that will set the block type to another block type.

## Extra Parameters

`set_block` can use the following parameters

|Name |Default Value  |Type  |Description  |
|:----------|:----------|:----------|:----------|
|block_type|*not set* |String| The type of block to set. |

## Example

```json
"set_block":{
    "block_type": "redstone"
}
```
