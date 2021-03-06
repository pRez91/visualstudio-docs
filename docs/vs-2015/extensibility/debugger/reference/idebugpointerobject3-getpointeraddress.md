---
title: "IDebugPointerObject3::GetPointerAddress | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
helpviewer_keywords: 
  - "GetPointerAddress"
  - "IDebugPointerObject3::GetPointerAddress"
ms.assetid: 4cc5af04-9e70-420d-8230-ef3108df6d51
caps.latest.revision: 9
ms.author: "gregvanl"
manager: "ghogen"
---
# IDebugPointerObject3::GetPointerAddress
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDebugPointerObject3::GetPointerAddress](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/idebugpointerobject3-getpointeraddress).  
  
Retrieves the address of the pointer.  
  
## Syntax  
  
```cpp#  
HRESULT GetPointerAddress (  
   UINT64* puAddress  
);  
```  
  
```csharp  
int GetPointerAddress (  
   out ulong puAddress  
);  
```  
  
#### Parameters  
 `puAddress`  
 [out] Returns the address of the pointer.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## See Also  
 [IDebugPointerObject3](../../../extensibility/debugger/reference/idebugpointerobject3.md)

