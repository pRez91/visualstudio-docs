---
title: "IDebugProcess3::GetDebugReason | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "IDebugProcess3::GetDebugReason"
helpviewer_keywords: 
  - "IDebugProcess3::GetDebugReason"
ms.assetid: f23fbabc-8b18-4278-bebf-4cdc7091513c
caps.latest.revision: 12
ms.author: "gregvanl"
manager: "ghogen"
---
# IDebugProcess3::GetDebugReason
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDebugProcess3::GetDebugReason](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/idebugprocess3-getdebugreason).  
  
This method returns the reason that the process was launched for debugging.  
  
## Syntax  
  
```cpp  
HRESULT GetDebugReason(  
   DEBUG_REASON* pReason  
);  
```  
  
```csharp  
int GetDebugReason(  
   out enum_DEBUG_REASON pReason  
);  
```  
  
#### Parameters  
 `pReason`  
 [out] Returns a value from the [DEBUG_REASON](../../../extensibility/debugger/reference/debug-reason.md) enumeration.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns error code.  
  
## See Also  
 [IDebugProcess3](../../../extensibility/debugger/reference/idebugprocess3.md)   
 [DEBUG_REASON](../../../extensibility/debugger/reference/debug-reason.md)

