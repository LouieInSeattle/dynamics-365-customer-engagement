---
title: Get a Data Connector Mapping Type (Hub)
description: Gets the specified Data Connector Mapping.
keywords: Customer Insights; Hub API; Data Connector Mapping; get
author: JimDaly
ms.author: jdaly
manager: jdaly
ms.date: 05/18/2017
ms.topic: reference
ms.service: customer-insights 
ms.assetid: 98986c28-da82-42e6-86d4-fcc8f3920027
---

Get a Data Connector Mapping Type (Hub)
======================================

[!include[pre release disclaimer](../../../includes/cc-beta-prerelease-disclaimer.md)]

Gets the specified Data [Connector Mapping](../types/connectormapping.md) definition for a Hub.

## Request 
The request is constructed as follows:

|**HTTP Verb**|**Request URI**|
|-------------|---------------|
|GET|`<hub-endpoint>/connectors/<connectorName>/mappings/<mappingName>?api-version=2017-04-26`|

### URI Parameters

|**URI Parameter**|**Required**|**Description**|
| --------------- | ---------- | ------------- |
|hub-endpoint|Yes|The base URL for your Customer Insights Hub|
|mappingName|Yes|Name of the data connector mapping to be retrieved|
| | | |


## Response  
 The response includes a standard HTTP status code, a set of standard response headers, and a response body.

#### Response Body  

The requested connector mapping information, including a [ConnectorMapping](../types/connector.md) type definition.

