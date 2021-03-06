---
title: "IDiaSession::findFileById | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-debug"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "IDiaSession::findFileById method"
ms.assetid: 710efe04-78b5-4f3e-a1d8-f9b069063503
caps.latest.revision: 12
author: "mikejo5000"
ms.author: "mikejo"
manager: "ghogen"
---
# IDiaSession::findFileById
[!INCLUDE[vs2017banner](../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDiaSession::findFileById](https://docs.microsoft.com/visualstudio/debugger/debug-interface-access/idiasession-findfilebyid).  
  
Retrieves a source file by source file identifier.  
  
## Syntax  
  
```cpp#  
HRESULT findFileById (   
   DWORD            uniqueId,  
   IDiaSourceFile** ppResult  
);  
```  
  
#### Parameters  
 `uniqueId`  
 [in] Specifies the source file identifier.  
  
 `ppResult`  
 [out] Returns an [IDiaSourceFile](../../debugger/debug-interface-access/idiasourcefile.md) object that represents the source file retrieved.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## Remarks  
 The source file identifier is a unique value used internally to the DIA SDK to make all source files unique. This method is typically used internally to the DIA SDK.  
  
## See Also  
 [IDiaSession](../../debugger/debug-interface-access/idiasession.md)   
 [IDiaSession::findFile](../../debugger/debug-interface-access/idiasession-findfile.md)   
 [IDiaSourceFile](../../debugger/debug-interface-access/idiasourcefile.md)



