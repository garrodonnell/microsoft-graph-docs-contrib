---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

// Code snippets are only available for the latest version. Current version is 5.x

// To initialize your graphClient, see https://learn.microsoft.com/en-us/graph/sdks/create-client?from=snippets&tabs=csharp
var result = await graphClient.Education.Reports.ReflectCheckInResponses.GetAsync((requestConfiguration) =>
{
	requestConfiguration.QueryParameters.Filter = "submitDateTime gt 2023-10-10T00:00:00.000Z";
});


```