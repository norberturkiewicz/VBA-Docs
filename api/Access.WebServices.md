---
title: WebServices object (Access)
keywords: vbaac10.chm14550
f1_keywords:
- vbaac10.chm14550
ms.prod: access
api_name:
- Access.WebServices
ms.assetid: 457074a3-89ff-7859-e833-9a7e6f57bc6a
ms.date: 06/08/2017
localization_priority: Normal
---


# WebServices object (Access)

Represents the collection of Data Services data connections installed in the database.


## Remarks

Use the [WebServices](Access.Application.WebServices.md) property of the [Application Object](Access.Application.md) to return the collection of installed Data Services data connections.

Use the following steps to install a Data Services data connection in your database.


1. Obtain a Data Services data connection file of the data source that you want to connect to.
    
2. On the ribbon, click the  **External Data** tab.
    
3. In the  **Import &amp; Link** group, click the **More** dropdown and then click **Data Services**.
    
4. At the bottom of the ** Create Link to Data Services** dialog box, click **Install New Connection**.
    
5. In the  **Select a connection definition file** dialog box, browse to and select the XML file that contains the description of the Data Service.
    

## Properties



|Name|
|:-----|
|[Application](Access.WebServices.Application.md)|
|[Count](Access.WebServices.Count.md)|
|[Item](Access.WebServices.Item.md)|
|[Parent](Access.WebServices.Parent.md)|

## See also


[Access Object Model Reference](overview/Access/object-model.md)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]