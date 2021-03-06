---
Description: The get\_BandwidthModifier method gets the bandwidth modifier, which is a single, alphanumeric word giving the meaning of the bandwidth figure. The two modifiers defined are CT (Conference Total) and AS (Application Specific Maximum).
ms.assetid: 29bf137d-e88b-437f-8bf1-824e335d47a1
title: ITConnection::get_BandwidthModifier method
ms.topic: article
ms.date: 05/31/2018
---

# ITConnection::get\_BandwidthModifier method

\[ Rendezvous IP Telephony Conferencing controls and interfaces are not available for use in Windows Vista, Windows Server 2008, and subsequent versions of the operating system. The RTC Client API provides similar functionality.\]

The **get\_BandwidthModifier** method gets the bandwidth modifier, which is a single, alphanumeric word giving the meaning of the bandwidth figure. The two modifiers defined are CT (Conference Total) and AS (Application Specific Maximum).

## Syntax


```C++
HRESULT get_BandwidthModifier(
  [out] BSTR *ppModifier
);
```



## Parameters

<dl> <dt>

*ppModifier* \[out\]
</dt> <dd>

Pointer to a **BSTR** containing the bandwidth modifier.

</dd> </dl>

## Return value

This method can return one of these values.



| Return code                                                                                   | Description                                                     |
|-----------------------------------------------------------------------------------------------|-----------------------------------------------------------------|
| <dl> <dt>**S\_OK**</dt> </dl>          | Method succeeded.<br/>                                    |
| <dl> <dt>**E\_POINTER**</dt> </dl>     | The *ppModifier* parameter is not a valid pointer.<br/>   |
| <dl> <dt>**E\_OUTOFMEMORY**</dt> </dl> | Insufficient memory exists to perform the operation.<br/> |
| <dl> <dt>**E\_FAIL**</dt> </dl>        | Unspecified error.<br/>                                   |
| <dl> <dt>**E\_NOTIMPL**</dt> </dl>     | This method is not yet implemented.<br/>                  |



 

## Remarks

The application must use [**SysFreeString**](https://msdn.microsoft.com/en-us/library/ms221481(v=VS.71).aspx) to free the memory allocated for the *ppModifier* parameter.

## Requirements



|                         |                                                                                       |
|-------------------------|---------------------------------------------------------------------------------------|
| TAPI version<br/> | Requires TAPI 3.0 or later<br/>                                                 |
| Header<br/>       | <dl> <dt>Sdpblb.h</dt> </dl>   |
| Library<br/>      | <dl> <dt>Uuid.lib</dt> </dl>   |
| DLL<br/>          | <dl> <dt>Sdpblb.dll</dt> </dl> |



## See also

<dl> <dt>

[**ITConnection**](itconnection.md)
</dt> </dl>

 

 




