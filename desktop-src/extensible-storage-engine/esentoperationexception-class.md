---
title: EsentOperationException class
TOCTitle: EsentOperationException class
ms:assetid: T:Microsoft.Isam.Esent.Interop.EsentOperationException
ms:mtpsurl: https://msdn.microsoft.com/library/microsoft.isam.esent.interop.esentoperationexception(v=EXCHG.10)
ms:contentKeyID: 55102414
ms.date: 07/30/2014
ms.topic: reference
f1_keywords:
- Microsoft.Isam.Esent.Interop.EsentOperationException
dev_langs:
- CSharp
- JScript
- VB
- other
api_name: 
- Microsoft.Isam.Esent.Interop.EsentOperationException
topic_type: 
- kbSyntax
- apiref
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# EsentOperationException class

Base class for Operation exceptions.

## Inheritance hierarchy

[System.Object](/dotnet/api/system.object)  
  [System.Exception](/dotnet/api/system.exception)  
    [Microsoft.Isam.Esent.EsentException](./esentexception-class.md)  
      [Microsoft.Isam.Esent.Interop.EsentErrorException](./esenterrorexception-class.md)  
        Microsoft.Isam.Esent.Interop.EsentOperationException  
          

**Namespace:**  [Microsoft.Isam.Esent.Interop](./microsoft.isam.esent.interop-namespace.md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
<SerializableAttribute> _
Public MustInherit Class EsentOperationException _
    Inherits EsentErrorException
'Usage
Dim instance As EsentOperationException
```

``` csharp
[SerializableAttribute]
public abstract class EsentOperationException : EsentErrorException
```

## Thread safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See also

#### Reference

[EsentOperationException members](./esentoperationexception-members.md)

[Microsoft.Isam.Esent.Interop namespace](./microsoft.isam.esent.interop-namespace.md)

## Derived types

[System.Object](/dotnet/api/system.object)  
  [System.Exception](/dotnet/api/system.exception)  
    [Microsoft.Isam.Esent.EsentException](./esentexception-class.md)  
      [Microsoft.Isam.Esent.Interop.EsentErrorException](./esenterrorexception-class.md)  
        Microsoft.Isam.Esent.Interop.EsentOperationException  
          [Microsoft.Isam.Esent.Interop.EsentBackupAbortByServerException](dn274014\(v=exchg.10\).md)  
          [Microsoft.Isam.Esent.Interop.EsentCheckpointDepthTooDeepException](dn274195\(v=exchg.10\).md)  
          [Microsoft.Isam.Esent.Interop.EsentClientRequestToStopJetServiceException](dn274150\(v=exchg.10\).md)  
          [Microsoft.Isam.Esent.Interop.EsentFatalException](dn274321\(v=exchg.10\).md)  
          [Microsoft.Isam.Esent.Interop.EsentInitInProgressException](dn350503\(v=exchg.10\).md)  
          [Microsoft.Isam.Esent.Interop.EsentInternalErrorException](dn319452\(v=exchg.10\).md)  
          [Microsoft.Isam.Esent.Interop.EsentIOException](dn319595\(v=exchg.10\).md)  
          [Microsoft.Isam.Esent.Interop.EsentNTSystemCallFailedException](dn334749\(v=exchg.10\).md)  
          [Microsoft.Isam.Esent.Interop.EsentOSSnapshotTimeOutException](dn319704\(v=exchg.10\).md)  
          [Microsoft.Isam.Esent.Interop.EsentRecordNotDeletedException](dn350508\(v=exchg.10\).md)  
          [Microsoft.Isam.Esent.Interop.EsentResourceException](dn350557\(v=exchg.10\).md)  
          [Microsoft.Isam.Esent.Interop.EsentTermInProgressException](dn334979\(v=exchg.10\).md)  
          [Microsoft.Isam.Esent.Interop.EsentUnicodeLanguageValidationFailureException](dn350816\(v=exchg.10\).md)  
          [Microsoft.Isam.Esent.Interop.EsentUnicodeTranslationFailException](dn350826\(v=exchg.10\).md)
