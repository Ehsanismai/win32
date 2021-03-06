---
title: SystemParameters.EventLoggingLevel property 
TOCTitle: 'EventLoggingLevel property '
ms:assetid: P:Microsoft.Isam.Esent.Interop.SystemParameters.EventLoggingLevel
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.isam.esent.interop.systemparameters.eventlogginglevel(v=EXCHG.10)
ms:contentKeyID: 55104119
ms.date: 07/30/2014
ms.topic: reference
f1_keywords:
- Microsoft.Isam.Esent.Interop.SystemParameters.EventLoggingLevel
dev_langs:
- CSharp
- JScript
- VB
- other
api_name: 
- Microsoft.Isam.Esent.Interop.SystemParameters.set_EventLoggingLevel
- Microsoft.Isam.Esent.Interop.SystemParameters.EventLoggingLevel
- Microsoft.Isam.Esent.Interop.SystemParameters.get_EventLoggingLevel
topic_type: 
- kbSyntax
- apiref
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# SystemParameters.EventLoggingLevel property

Gets or sets the detail level of eventlog messages that are emitted to the eventlog by the database engine. Higher numbers will result in more detailed eventlog messages.

**Namespace:**  [Microsoft.Isam.Esent.Interop](hh596136\(v=exchg.10\).md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
Public Shared Property EventLoggingLevel As Integer
    Get
    Set
'Usage
Dim value As Integer

value = SystemParameters.EventLoggingLevel

SystemParameters.EventLoggingLevel = value
```

``` csharp
public static int EventLoggingLevel { get; set; }
```

#### Property value

Type: [System.Int32](https://docs.microsoft.com/dotnet/api/system.int32?redirectedfrom=MSDN)  

## See also

#### Reference

[SystemParameters class](dn351139\(v=exchg.10\).md)

[SystemParameters members](dn351207\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop namespace](hh596136\(v=exchg.10\).md)

