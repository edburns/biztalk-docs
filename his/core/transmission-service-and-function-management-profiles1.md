---
description: "Learn more about: Transmission Service and Function Management Profiles"
title: "Transmission Service and Function Management Profiles1 | Microsoft Docs"
ms.custom: ""
ms.date: "11/30/2017"
ms.prod: "host-integration-server"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: c5d41531-a4ff-46f4-9f6b-7678b68b5e6c
caps.latest.revision: 4
author: "christopherhouser"
ms.author: "hisdocs"
manager: "anneta"
---
# Transmission Service and Function Management Profiles
[!INCLUDE[hisHostIntServNoVersion](../includes/hishostintservnoversion-md.md)] enforces the rules that govern active sessions between communicating partners on an SNA network.  
  
 The Host Integration Server computer can select some of these session protocols—such as request/response control modes, bracket usage, and pacing—when you activate a session. The term "profiles" refers to specific combinations of these selectable protocol options.  
  
 Transmission service (TS) profiles refer to transmission control options, while function management (FM) profiles refer to data flow control and function management data options.  
  
 When activated, TS and FM profiles of a session are specified by using parameters in the appropriate session activation request and response such as ACTPU, ACTLU, BIND.  
  
 The following table specifies the TS and FM profiles supported by each of the Host Integration Server session types.  
  
|Session type|TS profiles|FM profiles|  
|------------------|-----------------|-----------------|  
|SSCP-LU session|1|0|  
|SSCP-PU session|1|0|  
|3270 display and printer PLU-SLU session|3|3|  
|LU 6.2 PLU-SLU session|7|19|  
|LUA PLU-SLU session|2, 3, 4|2, 3, 4, 7, 18|  
  
## In This Section  
 [TS Profile 1](../core/ts-profile-12.md)  
  
 [TS Profile 2](../core/ts-profile-22.md)  
  
 [TS Profile 3](../core/ts-profile-31.md)  
  
 [TS Profile 4](../core/ts-profile-42.md)  
  
 [TS Profile 7](../core/ts-profile-72.md)  
  
 [FM Profile 0](../core/fm-profile-02.md)  
  
 [FM Profile 2](../core/fm-profile-21.md)  
  
 [FM Profile 3](../core/fm-profile-31.md)  
  
 [FM Profile 4](../core/fm-profile-42.md)  
  
 [FM Profile 7](../core/fm-profile-72.md)  
  
 [FM Profile 18](../core/fm-profile-182.md)  
  
 [FM Profile 19](../core/fm-profile-192.md)
