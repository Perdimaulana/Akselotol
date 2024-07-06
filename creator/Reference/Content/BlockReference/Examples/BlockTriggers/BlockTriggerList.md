---
author: JimSeaman42
ms.author: mikeam
title: Block Documentation - Block Trigger List
description: "A reference document listing all currently available block triggers"
ms.service: minecraft-bedrock-edition
---

# Block Documentation - Block Trigger

Below is a list of all available Block Triggers within Minecraft: Bedrock Edition for use with Block JSON files.

>[!IMPORTANT]
> Block Triggers require the Holiday Creator Features experimental toggle to be set to `true` in order to function properly.
>
>Holiday Creator Features contains experimental gameplay features. As with all experiments, you may see additions, removals, and changes in functionality in Minecraft versions without significant advanced warning.
>
>To learn more about Experimental Features, please visit [Experimental Features in Minecraft: Bedrock Edition](../../../../../Documents/ExperimentalFeaturesToggle.md).

## Block Trigger List

|Name |Default Value  |Type  |Description  |
|:----------|:----------|:----------|:----------|
|[minecraft:on_fall_on](minecraftBlock_on_fall_on.md)|*not set* | JSON Object| When an entity falls and lands on the block.|
|[minecraft:on_interact](minecraftBlock_on_interact.md)|*not set*  | JSON Object| When an entity interacts with a block.|
|[minecraft:on_placed](minecraftBlock_on_placed.md)|*not set*  | JSON Object| When an entity places a block in the world.|
|[minecraft:on_player_destroyed](minecraftBlock_on_player_destroyed.md)|*not set*  | JSON Object| When an entity, that is tagged as a player, destroys a block.|
|[minecraft:on_player_placing](minecraftBlock_on_player_placing.md)|*not set*  | JSON Object| When an entity, that is tagged as a player, places a block in the world.|
|[minecraft:on_step_off](minecraftBlock_on_step_off.md)|*not set*  | JSON Object| When an entity steps off the block.|
|[minecraft:on_step_on](minecraftBlock_on_step_on.md)|*not set*  |  JSON Object| When an entity steps on the block.|
|[minecraft:queued_ticking](minecraftBlock_queued_ticking.md)|*not set*  | JSON Object| Triggers the specified event, either once, or at a regular interval equal to a number of ticks randomly chosen from the interval_range provided.|
|[minecraft:random_ticking](minecraftBlock_random_ticking.md)|*not set*  | JSON Object| Triggers the specified event randomly based on the random tick speed game rule. The random tick speed determines how often blocks are updated.|
