---
title: "IDebugPropertyField::GetPropertyGetter | Microsoft Docs"
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
  - "IDebugPropertyField::GetPropertyGetter"
helpviewer_keywords: 
  - "IDebugPropertyField::GetPropertyGetter method"
ms.assetid: ab9f861a-42ad-4a82-9ae6-2606176f755a
caps.latest.revision: 10
ms.author: "gregvanl"
manager: "ghogen"
---
# IDebugPropertyField::GetPropertyGetter
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDebugPropertyField::GetPropertyGetter](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/idebugpropertyfield-getpropertygetter).  
  
Gets the method that gets the property.  
  
## Syntax  
  
```cpp#  
HRESULT GetPropertyGetter(   
   IDebugMethodField** ppField  
);  
```  
  
```cpp#  
int GetPropertyGetter(  
   out IDebugMethodField ppField  
);  
```  
  
#### Parameters  
 `ppField`  
 [out] Returns an [IDebugMethodField](../../../extensibility/debugger/reference/idebugmethodfield.md) object representing the method that gets the property.  
  
## Return Value  
 If successful, returns S_OK; otherwise, returns an error code.  
  
## Remarks  
 To get the method that sets the property, [GetPropertySetter](../../../extensibility/debugger/reference/idebugpropertyfield-getpropertysetter.md) call the method.  
  
## See Also  
 [IDebugPropertyField](../../../extensibility/debugger/reference/idebugpropertyfield.md)   
 [GetPropertySetter](../../../extensibility/debugger/reference/idebugpropertyfield-getpropertysetter.md)   
 [IDebugMethodField](../../../extensibility/debugger/reference/idebugmethodfield.md)

