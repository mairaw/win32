---
Description: The FileName property sets or retrieves the path to the executable file. This is the default property.
ms.assetid: 2d2ea87b-86db-40b4-b052-8503beafa08c
title: SignedCode.FileName property
ms.topic: article
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- SignedCode.FileName
api_type: 
- COM
api_location: 
- Capicom.dll
---

# SignedCode.FileName property

\[The **FileName** property is available for use in the operating systems specified in the Requirements section. Instead, use Platform Invocation Services (PInvoke) to call the Win32 API [**SignerSignEx**](signersignex.md), [**SignerTimeStampEx**](signertimestampex.md), and [**WinVerifyTrust**](/windows/desktop/api/Wintrust/nf-wintrust-winverifytrust) functions to sign content with an Authenticode digital signature. For information about PInvoke, see [Platform Invoke Tutorial](https://go.microsoft.com/fwlink/p/?linkid=119531). The [.NET and CryptoAPI via P/Invoke: Part 1](https://go.microsoft.com/fwlink/p/?linkid=119533) and [.NET and CryptoAPI via P/Invoke: Part 2](https://go.microsoft.com/fwlink/p/?linkid=119534) subsections of [Extending .NET Cryptography with CAPICOM and P/Invoke](https://go.microsoft.com/fwlink/p/?linkid=119532) may also be helpful.\]

The **FileName** property sets or retrieves the path to the executable file. This is the default property.

## Syntax


```VB
SignedCode.FileName As String
```



## Property value

The path to the executable file.

## Remarks

If the value of the **FileName** property is modified, the state of the entire [**SignedCode**](signedcode.md) object is reset.

## Requirements



|                            |                                                                                        |
|----------------------------|----------------------------------------------------------------------------------------|
| Redistributable<br/> | CAPICOM 2.0 or later on Windows Server 2003 and Windows XP<br/>                  |
| DLL<br/>             | <dl> <dt>Capicom.dll</dt> </dl> |



## See also

<dl> <dt>

[**SignedCode**](signedcode.md)
</dt> </dl>

 

 




