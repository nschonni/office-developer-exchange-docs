---
title: "PlayOnPhone (Exchange Web Services)"
 
 
manager: sethgros
ms.date: 9/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- PlayOnPhone
api_type:
- schema
ms.assetid: 486612be-470c-4f99-929a-f2b283e055c1
description: "The PlayOnPhone element represents a request to read an item on a phone."
---

# PlayOnPhone (Exchange Web Services)

The **PlayOnPhone** element represents a request to read an item on a phone. 
  
```
<PlayOnPhone>   <ItemId/>   <DialString/></PlayOnPhone>
```

 **PlayOnPhoneType**
## Attributes and elements

The following sections describe attributes, child elements, and parent elements.
  
#### Attributes

None.
  
#### Child elements

|**Element**|**Description**|
|:-----|:-----|
|[ItemId](itemid.md) <br/> |Represents the identifier of an item to play on a phone. This element is required.  <br/> |
|[DialString (Exchange Web Services)](dialstring-exchange-web-services.md) <br/> |Represents the dial string of the phone number that is called to play an item by phone. This element is required.  <br/> |
   
#### Parent elements

None.
  
## Remarks

The schema that describes this element is located in the EWS virtual directory of the computer that is running Microsoft Exchange Server 2010 that has the Client Access server role installed.
  
## Element information

|||
|:-----|:-----|
|Namespace  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|Schema Name  <br/> |Messages schema  <br/> |
|Validation File  <br/> |Messages.xsd  <br/> |
|Can be Empty  <br/> |False  <br/> |
   
## See also

#### Concepts

[EWS XML elements in Exchange](ews-xml-elements-in-exchange.md)
