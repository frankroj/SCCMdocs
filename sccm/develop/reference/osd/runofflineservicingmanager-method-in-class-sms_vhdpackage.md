---
title: "RunOfflineServicingManager Method in SMS_VhdPackage"
titleSuffix: "Configuration Manager"
ms.date: "09/20/2016"
ms.prod: "configuration-manager"
ms.technology: configmgr-sdk
ms.topic: conceptual
ms.assetid: e660da6d-b07b-4084-99aa-ef6b7d9fe1f4
author: aczechowski
ms.author: aaroncz
manager: dougeby
---
# RunOfflineServicingManager Method in Class SMS_VhdPackage
The `RunOfflineServicingManager` Windows Management Instrumentation (WMI) class method, in Configuration Manager, that updates the site control file of the offline servicing manager to run the offline image servicing component as soon as possible on the specified operating system image at the specified site server.  

 The following syntax is simplified from Managed Object Format (MOF) code and defines the method.  

## Syntax  

```  
uint32 RunOfflineServicingManager   
{  
    String SiteCode  
    String ServerName  
    String PackageID  
};  
```  

## Parameters  
 `SiteCode`  
 Data type: `String`  

 Qualifiers: [id("0"), in]  

 Site code of the site where offline servicing of the operating system image is requested.  

 `ServerName`  
 Data type: `String`  

 Qualifiers: [id("1"), in]  

 Name of the site server where offline servicing of the operating system is requested (server1.domain1.net).  

 `PackageID`  
 Data type: `String`  

 Qualifiers: [id("2"), in]  

 The package identifier of the operating system image to be patched with software updates through offline servicing.  

## Remarks  

## Requirements  

## Runtime Requirements  
 For more information, see [Configuration Manager Server Runtime Requirements](../../../develop/core/reqs/server-runtime-requirements.md).  

## Development Requirements  
 For more information, see [Configuration Manager Server Development Requirements](../../../develop/core/reqs/server-development-requirements.md).
