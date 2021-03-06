---
Description: Retrieves the Signer object that represents the indexed signer.
ms.assetid: a95f4e33-ab92-44e1-91ab-2c5335a04f05
title: Signers.Item property
ms.topic: article
ms.date: 05/31/2018
topic_type:
- APIRef
- kbSyntax
api_name:
- Signers.Item
api_type:
- COM
api_location:
- Capicom.dll
---

# Signers.Item property

\[The **Item** property is available for use in the operating systems specified in the Requirements section. Instead, use a collection of CmsSigner objects. For more information, see the [**CmsSigner Class**](https://msdn.microsoft.com/library/5x3db70t(v=VS.100).aspx) in the [**System.Security.Cryptography.Pkcs**](https://msdn.microsoft.com/library/6see7k14(v=VS.100).aspx) namespace.\]

The **Item** property retrieves the [**Signer**](signer.md) object that represents the indexed signer. This is the default property.

## Syntax


```VB
Signers.Item( _
  ByVal Index _
) As Variant
```



## Property value

The [**Signer**](signer.md) object that represents the indexed signer.

## Requirements



|                            |                                                                                        |
|----------------------------|----------------------------------------------------------------------------------------|
| Redistributable<br/> | CAPICOM 2.0 or later on Windows Server 2003 and Windows XP<br/>                  |
| DLL<br/>             | <dl> <dt>Capicom.dll</dt> </dl> |



## See also

<dl> <dt>

[**Signers**](signers.md)
</dt> </dl>

 

 




