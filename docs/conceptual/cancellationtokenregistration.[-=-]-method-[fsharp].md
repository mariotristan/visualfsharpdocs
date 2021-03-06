---
title: CancellationTokenRegistration.( = ) Method (F#)
description: CancellationTokenRegistration.( = ) Method (F#)
keywords: visual f#, f#, functional programming
author: dend
manager: danielfe
ms.date: 05/16/2016
ms.topic: language-reference
ms.prod: visual-studio-dev14
ms.assetid: c6d0a2bb-0c9f-4a82-8365-62bebc2d5c2d 
---

# CancellationTokenRegistration.( = ) Method (F#)

Equality operator for registrations.

**Namespace/Module Path**: System.Threading

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## Syntax

```fsharp
// Signature:
static member ( = ) : CancellationTokenRegistration * CancellationTokenRegistration -> bool

// Usage:
registration1 = registration2
```

#### Parameters
*registration1*
Type: [CancellationTokenRegistration](https://msdn.microsoft.com/library/9696e15c-a160-4336-9c5c-6277eaa1e1d1)


The first input registration.


*registration2*
Type: [CancellationTokenRegistration](https://msdn.microsoft.com/library/9696e15c-a160-4336-9c5c-6277eaa1e1d1)


The second input registration.


## Return Value
True if the two registrations are equal.

## Remarks
This API is provided for use only with the F# Core Library Versions that targets .NET Framework 2.0. If you are using .NET Framework 4, use the .NET Framework 4 API with the same name, **M:System.Threading.CancellationTokenRegistration.op_Equality(System.Threading.CancellationTokenRegistration,System.Threading.CancellationTokenRegistration)**.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0




## See Also
[Threading.CancellationTokenRegistration Structure &#40;F&#35;&#41;](Threading.CancellationTokenRegistration-Structure-%5BFSharp%5D.md)

[System.Threading Namespace &#40;F&#35;&#41;](System.Threading-Namespace-%5BFSharp%5D.md)

