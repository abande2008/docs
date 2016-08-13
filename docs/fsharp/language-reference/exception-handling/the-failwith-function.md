---
title: Exceptions - The failwith Function (F#)
description: Exceptions - The failwith Function (F#)
keywords: visual f#, f#, functional programming
author: dend
manager: danielfe
ms.date: 05/16/2016
ms.topic: language-reference
ms.prod: visual-studio-dev14
ms.technology: devlang-fsharp
ms.assetid: 2e0c1f28-cc6c-4ecd-bb93-3816c4dd7cd3 
---

# Exceptions: The failwith Function

The `failwith` function generates an F# exception.


## Syntax

```fsharp
failwith error-message-string
```

## Remarks
The *error-message-string* in the previous syntax is a literal string or a value of type `string`. It becomes the `Message` property of the exception.

The exception that is generated by `failwith` is a `System.Exception` exception, which is a reference that has the name `Failure` in F# code. The following code illustrates the use of `failwith` to throw an exception.

[!code-fsharp[Main](../../../../samples/fsharp/lang-ref-2/snippet6001.fs)]
    
## See Also
[Exception Handling](index.md)

[Exception Types](exception-types.md)

[Exceptions: The `try...with` Expression](the-try-with-expression.md)

[Exceptions: The `try...finally` Expression](the-try-finally-expression.md)

[Exceptions: the `raise` Function](the-raise-function.md)