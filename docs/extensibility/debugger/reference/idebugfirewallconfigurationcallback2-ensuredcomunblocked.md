---
description: "Requests that the firewall not block remote debugging."
title: IDebugFirewallConfigurationCallback2::EnsureDCOMUnblocked
titleSuffix: ""
ms.date: 11/04/2016
ms.topic: reference
helpviewer_keywords:
- EnsureDCOMUnblocked
- IDebugFirewallConfigurationCallback2::EnsureDCOMUnblocked
ms.assetid: acf54d27-32a6-47e7-aba6-3cc0004edc7f
author: maiak
ms.author: maiak
manager: jmartens
ms.technology: vs-ide-debug
ms.workload:
- vssdk
dev_langs:
- CPP
- CSharp
---
# IDebugFirewallConfigurationCallback2::EnsureDCOMUnblocked

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]

Requests that the firewall not block remote debugging.

## Syntax

### [C#](#tab/csharp)
```csharp
public int EnsureDCOMUnblocked();
```
### [C++](#tab/cpp)
```cpp
HRESULT EnsureDCOMUnblocked(
    Void
);
```
---

## Return Value

 If successful, returns `S_OK`; otherwise, returns an error code.

## See also

- [IDebugFirewallConfigurationCallback2](../../../extensibility/debugger/reference/idebugfirewallconfigurationcallback2.md)
