---
title: "Service: Security Calls Not Authorized Per Second"
ms.date: "03/30/2017"
ms.assetid: 1eeade5a-ea62-4757-b1f9-1b1b1746abd1
author: "BrucePerlerMS"
manager: "mbaldwin"
---
# Service: Security Calls Not Authorized Per Second
Counter name: Security Calls Not Authorized Per Second  
  
## Description  
 Number of incoming messages in one second, which are from a valid user and protected properly, but the user is not authorized to do specific tasks.  
  
 This counter is incremented when the <xref:System.ServiceModel.ServiceAuthorizationManager.CheckAccess%2A> method returns `false`.  
  
 This counter is of performance counter type [PERF_COUNTER_COUNTER](http://go.microsoft.com/fwlink/?LinkId=94649), whose value is calculated using the following formula.  
  
 (N 1 - N 0 ) / ( (D 1 -D 0 ) / F)
