---
title: HashCompare.FastCompareTuple5<'T1,'T2,'T3,'T4,'T5> Function (F#)
description: HashCompare.FastCompareTuple5<'T1,'T2,'T3,'T4,'T5> Function (F#)
keywords: visual f#, f#, functional programming
author: dend
manager: danielfe
ms.date: 05/16/2016
ms.topic: language-reference
ms.prod: visual-studio-dev14
ms.assetid: 4a797af0-4c65-4853-a072-b2a5fdb08aff 
---

# HashCompare.FastCompareTuple5<'T1,'T2,'T3,'T4,'T5> Function (F#)

A primitive entry point used by the F# compiler for optimization purposes.

**Namespace/Module Path:** Microsoft.FSharp.Core.LanguagePrimitives.HashCompare

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax

```
// Signature:
FastCompareTuple5 : IComparer -> 'T1 * 'T2 * 'T3 * 'T4 * 'T5 -> 'T1 * 'T2 * 'T3 * 'T4 * 'T5 -> int

// Usage:
FastCompareTuple5 comparer tuple1 tuple2
```

#### Parameters
*comparer*
Type: **T:System.Collections.IComparer**


The comparer object.


*tuple1*
Type: **'T1 &#42; 'T2 &#42; 'T3 &#42; 'T4 &#42; 'T5**


The first tuple of five elements.


*tuple2*
Type: **'T1 &#42; 'T2 &#42; 'T3 &#42; 'T4 &#42; 'T5**


The second tuple of five elements.



**The result of the comparison.**
## Remarks
This function is for use by compiled F# code and should not be used directly.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[LanguagePrimitives.HashCompare Module &#40;F&#35;&#41;](LanguagePrimitives.HashCompare-Module-%5BFSharp%5D.md)

[Core.LanguagePrimitives Module &#40;F&#35;&#41;](Core.LanguagePrimitives-Module-%5BFSharp%5D.md)

