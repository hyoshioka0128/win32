---
title: EsentUsageException constructor (String, JET_err) (Microsoft.Isam.Esent.Interop)
TOCTitle: EsentUsageException constructor (String, JET_err)
ms:assetid: M:Microsoft.Isam.Esent.Interop.EsentUsageException.#ctor(System.String,Microsoft.Isam.Esent.Interop.JET_err)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.isam.esent.interop.esentusageexception.esentusageexception(v=EXCHG.10)
ms:contentKeyID: 55103223
ms.date: 07/30/2014
ms.topic: article
dev_langs:
- vb
- csharp
api_name: 
- Microsoft.Isam.Esent.Interop.EsentUsageException..ctor
topic_type: 
- apiref
- kbSyntax
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# EsentUsageException constructor (String, JET_err)

Initializes a new instance of the EsentUsageException class.

**Namespace:**  [Microsoft.Isam.Esent.Interop](hh596136\(v=exchg.10\).md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    description As String, _
    err As JET_err _
)
'Usage
Dim description As String
Dim err As JET_err

Dim instance As New EsentUsageException(description, _
    err)
```

``` csharp
protected EsentUsageException(
    string description,
    JET_err err
)
```

#### Parameters

  - description  
    Type: [System.String](https://docs.microsoft.com/dotnet/api/system.string?redirectedfrom=MSDN)  
    
    The description of the error.

<!-- end list -->

  - err  
    Type: [Microsoft.Isam.Esent.Interop.JET_err](hh564840\(v=exchg.10\).md)  
    
    The error code of the exception.

## See also

#### Reference

[EsentUsageException class](dn350849\(v=exchg.10\).md)

[EsentUsageException members](dn350859\(v=exchg.10\).md)

[EsentUsageException overload](dn350852\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop namespace](hh596136\(v=exchg.10\).md)

