---
title: "identityBuiltInUserFlowAttribute resource type"
description: "Represents a built-in user flow attribute that can be used in self-service sign-up user flows in Microsoft Entra External ID in workforce and external tenants, and in Azure AD B2C tenants."
author: "nanguil"
ms.localizationpriority: medium
ms.subservice: "entra-sign-in"
doc_type: resourcePageType
ms.date: 05/22/2024
---

# identityBuiltInUserFlowAttribute resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Represents a built-in user flow attribute that can be used in self-service sign-up user flows in Microsoft Entra External ID in workforce and external tenants, and in Azure AD B2C tenants. These attributes can't be modified and are read-only.

Inherits from [identityUserFlowAttribute](../resources/identityuserflowattribute.md).

## Properties

|Property|Type|Description|
|:---|:---|:---|
|dataType|identityUserFlowAttributeDataType|The data type of the user flow attribute and can't be modified after the custom user flow attribute is created. The supported values for **dataType** are: `string` , `boolean` , `int64` , `stringCollection` , `dateTime`. Inherited from [identityUserFlowAttribute](../resources/identityuserflowattribute.md). Read-only.|
|displayName|String|The display name of the user flow attribute. Inherited from [identityUserFlowAttribute](../resources/identityuserflowattribute.md). Read-only.|
|description|String|The description of the user flow attribute that's shown to the user at the time of sign up. Inherited from [identityUserFlowAttribute](../resources/identityuserflowattribute.md). Read-only.|
|id|String|The identifier of the user flow attribute. Read-only. Inherited from [identityUserFlowAttribute](../resources/identityuserflowattribute.md)|
|userFlowAttributeType|identityUserFlowAttributeType|The type of the user flow attribute and is a read-only attribute that is automatically set. The value for this property is `builtIn`. Inherited from [identityUserFlowAttribute](../resources/identityuserflowattribute.md). Read-only.|

## Relationships

None.

## JSON representation

The following JSON representation shows the resource type.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.identityBuiltInUserFlowAttribute",
  "baseType": "microsoft.graph.identityUserFlowAttribute",
  "openType": false
}
-->

``` json
{
  "@odata.type": "#microsoft.graph.identityBuiltInUserFlowAttribute",
  "id": "String (identifier)",
  "displayName": "String",
  "description": "String",
  "userFlowAttributeType": "String",
  "dataType": "String"
}
```
