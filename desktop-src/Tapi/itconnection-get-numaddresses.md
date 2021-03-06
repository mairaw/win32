---
Description: The get\_NumAddresses method gets the number of addresses to be used for the session.
ms.assetid: c3aef5df-02e9-4c7e-99aa-8e4043798bf4
title: ITConnection::get_NumAddresses method
ms.topic: article
ms.date: 05/31/2018
---

# ITConnection::get\_NumAddresses method

\[ Rendezvous IP Telephony Conferencing controls and interfaces are not available for use in Windows Vista, Windows Server 2008, and subsequent versions of the operating system. The RTC Client API provides similar functionality.\]

The **get\_NumAddresses** method gets the number of addresses to be used for the session.

## Syntax


```C++
HRESULT get_NumAddresses(
  [out] LONG *pNumAddresses
);
```



## Parameters

<dl> <dt>

*pNumAddresses* \[out\]
</dt> <dd>

Number of addresses for the session.

</dd> </dl>

## Return value

This method can return one of these values.



| Return code                                                                                   | Description                                                      |
|-----------------------------------------------------------------------------------------------|------------------------------------------------------------------|
| <dl> <dt>**S\_OK**</dt> </dl>          | Method succeeded.<br/>                                     |
| <dl> <dt>**E\_POINTER**</dt> </dl>     | The *pNumAddresse*s parameter is not a valid pointer.<br/> |
| <dl> <dt>**E\_OUTOFMEMORY**</dt> </dl> | Insufficient memory exists to perform the operation.<br/>  |
| <dl> <dt>**E\_FAIL**</dt> </dl>        | Unspecified error.<br/>                                    |
| <dl> <dt>**E\_NOTIMPL**</dt> </dl>     | This method is not yet implemented.<br/>                   |



 

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

 

 




