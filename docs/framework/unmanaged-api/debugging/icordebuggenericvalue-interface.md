---
title: "ICorDebugGenericValue 接口 1"
ms.custom: 
ms.date: 03/30/2017
ms.prod: .net-framework
ms.reviewer: 
ms.suite: 
ms.technology: dotnet-clr
ms.tgt_pltfrm: 
ms.topic: reference
api_name: ICorDebugGenericValue
api_location: mscordbi.dll
api_type: COM
f1_keywords: ICorDebugGenericValue
helpviewer_keywords: ICorDebugGenericValue interface [.NET Framework debugging]
ms.assetid: bc14f408-b359-4c8c-ade2-888ccdf7261b
topic_type: apiref
caps.latest.revision: "12"
author: rpetrusha
ms.author: ronpet
manager: wpickett
ms.workload: dotnet
ms.openlocfilehash: d6c6fb4893edf0bcda9d6f7ddbeea7054f5b4fd5
ms.sourcegitcommit: 16186c34a957fdd52e5db7294f291f7530ac9d24
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 12/22/2017
---
# <a name="icordebuggenericvalue-interface1"></a>ICorDebugGenericValue 接口 1
"ICorDebugValue"适用于所有值的一个子类。 此接口可为值提供 Get 和 Set 方法。  
  
## <a name="methods"></a>方法  
  
|方法|描述|  
|------------|-----------------|  
|[GetValue 方法](../../../../docs/framework/unmanaged-api/debugging/icordebuggenericvalue-getvalue-method.md)|将值复制到指定的缓冲区。|  
|[SetValue 方法](../../../../docs/framework/unmanaged-api/debugging/icordebuggenericvalue-setvalue-method.md)|从指定的缓冲区中复制新值。|  
  
## <a name="remarks"></a>备注  
 `ICorDebugGenericValue`是一个子接口，因为它是非远程操作。  
  
 对于引用类型，则这是引用而不是该引用的内容。  
  
 此接口不支持跨计算机或跨进程远程调用。  
  
> [!NOTE]
>  此接口不支持跨计算机或跨进程远程调用。  
  
## <a name="requirements"></a>惠?  
 **平台：**请参阅[系统要求](../../../../docs/framework/get-started/system-requirements.md)。  
  
 **标头：** CorDebug.idl、 CorDebug.h  
  
 **库：** CorGuids.lib  
  
 **.NET framework 版本：**[!INCLUDE[net_current_v10plus](../../../../includes/net-current-v10plus-md.md)]  
  
## <a name="see-also"></a>请参阅  
    
 [调试接口](../../../../docs/framework/unmanaged-api/debugging/debugging-interfaces.md)
