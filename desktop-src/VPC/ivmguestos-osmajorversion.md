---
title: IVMGuestOS OSMajorVersion property
description: The major version of the guest operating system running in the virtual machine.
ms.assetid: c9be8b4e-15fe-402d-8396-30be6b065b73
keywords:
- OSMajorVersion property Virtual PC
- OSMajorVersion property Virtual PC , IVMGuestOS interface
- IVMGuestOS interface Virtual PC , OSMajorVersion property
topic_type:
- apiref
api_name:
- IVMGuestOS.OSMajorVersion
- IVMGuestOS.get_OSMajorVersion
api_location:
- VPCCOMInterfaces.h
api_type:
- COM
ms.topic: article
ms.date: 05/31/2018
---

# IVMGuestOS::OSMajorVersion property

\[Windows Virtual PC is no longer available for use as of Windows 8. Instead, use the [Hyper-V WMI provider (V2)](https://docs.microsoft.com/windows/desktop/HyperV_v2/windows-virtualization-portal).\]

Retrieves the major version of the guest operating system running in the virtual machine.

This property is read-only.

## Syntax


```C++
HRESULT get_OSMajorVersion(
  [out, retval] BSTR *majorVersion
);
```



## Property value

The major version.

## Error codes



| Name/value                                                                                                                                                                       | Meaning                                                         |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------|
| <dl> <dt>S\_OK</dt> <dt>0</dt> </dl>                                          | The operation was successful.<br/>                        |
| <dl> <dt>E\_POINTER</dt> <dt>0x80004003</dt> </dl>                            | The parameter is **NULL**.<br/>                           |
| <dl> <dt>VM\_E\_VM\_NOT\_RUNNING</dt> <dt>0xA0040206</dt> </dl>               | The VM is not running.<br/>                               |
| <dl> <dt>VM\_E\_ADDITIONS\_FEATURE\_NOT\_AVAIL</dt> <dt>0xA0040505</dt> </dl> | Integration components are not installed in this VM.<br/> |
| <dl> <dt>DISP\_E\_EXCEPTION</dt> <dt>0x80020009</dt> </dl>                    | An unexpected error has occurred.<br/>                    |



## Requirements



|                                     |                                                                                               |
|-------------------------------------|-----------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 7 \[desktop apps only\]<br/>                                                    |
| Minimum supported server<br/> | None supported<br/>                                                                     |
| End of client support<br/>    | Windows 7<br/>                                                                          |
| Product<br/>                  | Windows Virtual PC<br/>                                                                 |
| Header<br/>                   | <dl> <dt>VPCCOMInterfaces.h</dt> </dl> |
| IID<br/>                      | IID\_IVMGuestOS is defined as 99fea0db-4880-499a-b6d8-73dff9bc91be<br/>                 |



## See also

<dl> <dt>

[**IVMGuestOS**](ivmguestos.md)
</dt> </dl>

 

 





