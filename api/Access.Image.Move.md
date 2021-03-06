---
title: Image.Move method (Access)
keywords: vbaac10.chm10405
f1_keywords:
- vbaac10.chm10405
ms.prod: access
api_name:
- Access.Image.Move
ms.assetid: feda7964-0d93-b3e2-36b1-5c68054cdff1
ms.date: 06/08/2017
localization_priority: Normal
---


# Image.Move method (Access)

Moves the specified object to the coordinates specified by the argument values.


## Syntax

_expression_.**Move** (_Left_, _Top_, _Width_, _Height_)

_expression_ A variable that represents an [Image](Access.Image.md) object.


## Parameters



|Name|Required/Optional|Data type|Description|
|:-----|:-----|:-----|:-----|
| _Left_|Required|**Variant**|The screen position in [twips](../language/glossary/vbe-glossary.md#twip) for the left edge of the object relative to the left edge of the Microsoft Access window.|
| _Top_|Optional|**Variant**|The screen position in [twips](../language/glossary/vbe-glossary.md#twip) for the top edge of the object relative to the top edge of the Microsoft Access window.|
| _Width_|Optional|**Variant**|The desired width in [twips](../language/glossary/vbe-glossary.md#twip) of the object.|
| _Height_|Optional|**Variant**|The desired height in [twips](../language/glossary/vbe-glossary.md#twip) of the object.|

## Remarks

Only the  _Left_ argument is required. However, to specify any other arguments, you must specify all the arguments that precede it. For example, you cannot specify _Width_ without specifying _Left_ and _Top_. Any trailing arguments that are unspecified remain unchanged.

This method overrides the  **Moveable** property.

In Datasheet View or Print Preview, changes made using the  **Move** method are saved if the user explicitly saves the database, but Access does not prompt the user to save such changes.


## See also


[Image Object](Access.Image.md)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]