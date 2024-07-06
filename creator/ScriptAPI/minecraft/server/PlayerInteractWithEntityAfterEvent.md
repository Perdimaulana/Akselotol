---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.service: minecraft-bedrock-edition
title: minecraft/server.PlayerInteractWithEntityAfterEvent Class
description: Contents of the @minecraft/server.PlayerInteractWithEntityAfterEvent class.
---
# PlayerInteractWithEntityAfterEvent Class

Contains information regarding an event after a player interacts with an entity.

## Properties

### **itemStack**
`read-only itemStack?: ItemStack;`

The item stack that is being used in the interaction, or undefined if empty hand.

Type: [*ItemStack*](ItemStack.md)

### **player**
`read-only player: Player;`

Source Player for this event.

Type: [*Player*](Player.md)

### **target**
`read-only target: Entity;`

The entity that will be interacted with.

Type: [*Entity*](Entity.md)
