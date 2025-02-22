---
title: "timeOffRequest resource type"
description: "Represents a type of shift request to take timeOff."
ms.localizationpriority: medium
author: "akumar39"
ms.subservice: "teams"
doc_type: "resourcePageType"
ms.date: 07/22/2024
---

# timeOffRequest resource type

Namespace: microsoft.graph

Represents a type of shift request to take [timeOff](../resources/timeoff.md).

## Methods

| Method       | Return Type | Description |
|:-------------|:------------|:------------|
| [Get](../api/timeoffrequest-get.md) | [timeOffRequest](timeoffrequest.md) | Read the properties and relationships of a **timeOffRequest** object. |
| [List](../api/timeoffrequest-list.md) | [timeOffRequest](timeoffrequest.md) collection | Get the list of **timeOffRequest** objects in this schedule.|
| [Delete](../api/timeoffrequest-delete.md) | None | Delete a **timeOffRequest** object. |
| [Approve](../api/timeoffrequest-approve.md)|None|Approve a time off request.|
| [Decline](../api/timeoffrequest-decline.md)|None|Decline a time off request.|

## Properties

| Property     | Type        | Description |
|:-------------|:------------|:------------|
|endDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|startDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|timeOffReasonId|String|The reason for the time off.|

## Relationships

None.

## JSON representation

The following JSON representation shows the resource type.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.timeOffRequest"
}-->

```json
{
  "endDateTime": "String (timestamp)",
  "startDateTime": "String (timestamp)",
  "timeOffReasonId": "String"
}
```

<!-- uuid: 16cd6b66-4b1a-43a1-adaf-3a886856ed98
2019-02-04 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "timeOffRequest resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->

