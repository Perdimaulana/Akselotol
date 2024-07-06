---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.service: minecraft-bedrock-edition
title: minecraft/server-editor.WidgetGroup Class
description: Contents of the @minecraft/server-editor.WidgetGroup class.
---
# WidgetGroup Class

## Properties

### **valid**
`read-only valid: boolean;`

Type: *boolean*

## Methods
- [areAnySelected](#areanyselected)
- [createCustomWidget](#createcustomwidget)
- [deleteWidget](#deletewidget)
- [deselectAllWidgets](#deselectallwidgets)
- [getIsVisible](#getisvisible)
- [moveSelectedWidgets](#moveselectedwidgets)
- [selectAllWidgets](#selectallwidgets)
- [setIsVisible](#setisvisible)

### **areAnySelected**
`
areAnySelected(): boolean
`

**Returns** *boolean*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **createCustomWidget**
`
createCustomWidget(customEntityName: string, location: minecraftserver.Vector3, rotation?: minecraftserver.Vector2, options?: CustomWidgetCreateOptions): CustomWidget
`

#### **Parameters**
- **customEntityName**: *string*
- **location**: [*@minecraft/server.Vector3*](../../minecraft/server/Vector3.md)
- **rotation**?: [*@minecraft/server.Vector2*](../../minecraft/server/Vector2.md) = `null`
- **options**?: [*CustomWidgetCreateOptions*](CustomWidgetCreateOptions.md) = `null`

**Returns** [*CustomWidget*](CustomWidget.md)

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.

### **deleteWidget**
`
deleteWidget(widgetToDelete: Widget): void
`

#### **Parameters**
- **widgetToDelete**: [*Widget*](Widget.md)

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.

### **deselectAllWidgets**
`
deselectAllWidgets(): void
`

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **getIsVisible**
`
getIsVisible(): boolean
`

**Returns** *boolean*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **moveSelectedWidgets**
`
moveSelectedWidgets(delta: minecraftserver.Vector3): void
`

#### **Parameters**
- **delta**: [*@minecraft/server.Vector3*](../../minecraft/server/Vector3.md)

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **selectAllWidgets**
`
selectAllWidgets(): void
`

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **setIsVisible**
`
setIsVisible(isVisible: boolean): void
`

#### **Parameters**
- **isVisible**: *boolean*

> [!IMPORTANT]
> This function can't be called in read-only mode.
