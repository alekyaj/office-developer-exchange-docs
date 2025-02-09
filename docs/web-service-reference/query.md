---
title: "Query"
 
 
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.technology: ews
ms.localizationpriority: medium
ms.assetid: ccb4cd62-9779-4ca7-a4fe-5a96e6af8f48
description: "The Query element contains the search query for the hold."
---

# Query

The **Query** element contains the search query for the hold. 
  
```XML
<Query></Query>
```

 **string**
## Attributes and elements

The following sections describe attributes, child elements, and parent elements.
  
### Attributes

None.
  
### Child elements

None.
  
### Parent elements

[SetHoldOnMailboxes](setholdonmailboxes.md) | [MailboxHoldResult](mailboxholdresult.md) | [MailboxQuery](mailboxquery.md)
  
## Text value

The text value of the **Query** element is the search query string for a discovery search. 
  
## Remarks

This element was introduced in Exchange Server 2013.
  
The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.
  
## Element information

| Element | Example |
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|Schema name  <br/> |Messages schema  <br/> |
|Validation file  <br/> |Messages.xsd  <br/> |
|Can be empty  <br/> ||
   

