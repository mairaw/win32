---
title: MDM_Policy_Config01_DeviceGuard02 class
description: The MDM\_Policy\_Config01\_DeviceGuard02 configures the Device Guard policies.
ms.assetid: b8edf906-2486-4d8d-9410-d216bacf1728
keywords:
- MDM_Policy_Config01_DeviceGuard02 class
- MDM_Policy_Config01_DeviceGuard02 class, described
topic_type:
- apiref
api_name:
- MDM_Policy_Config01_DeviceGuard02
- MDM_Policy_Config01_DeviceGuard02.InstanceID
- MDM_Policy_Config01_DeviceGuard02.ParentID
api_location:
- DMWmiBridgeProv.dll
api_type:
- DllExport
ms.topic: article
ms.date: 05/31/2018
---

# MDM\_Policy\_Config01\_DeviceGuard02 class

\[Some information relates to pre-released product which may be substantially modified before it's commercially released. Microsoft makes no warranties, express or implied, with respect to the information provided here.\]

The MDM\_Policy\_Config01\_DeviceGuard02 configures the Device Guard policies.

The following syntax is simplified from MOF code and includes all inherited properties.

## Syntax

``` syntax
[InPartition("local-system"), dynamic, provider("DMWmiBridgeProv")]
class MDM_Policy_Config01_DeviceGuard02
{
  string InstanceID;
  string ParentID;
  sint32 EnableVirtualizationBasedSecurity;
  sint32 LsaCfgFlags;
  sint32 RequirePlatformSecurityFeatures;
};
```

## Members

The **MDM\_Policy\_Config01\_DeviceGuard02** class has these types of members:

-   [Properties](#properties)

### Properties

The **MDM\_Policy\_Config01\_DeviceGuard02** class has these properties.

<dl> <dt>

[EnableVirtualizationBasedSecurity](https://docs.microsoft.com/windows/client-management/mdm/policy-csp-deviceguard#deviceguard-enablevirtualizationbasedsecurity)
</dt> <dd> <dl> <dt>

Data type: **sint32**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> <dt>

**InstanceID**
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**key**](https://docs.microsoft.com/windows/desktop/WmiSdk/key-qualifier)
</dt> </dl>

</dd> <dt>

[LsaCfgFlags](https://docs.microsoft.com/windows/client-management/mdm/policy-csp-deviceguard#deviceguard-lsacfgflags)
</dt> <dd> <dl> <dt>

Data type: **sint32**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> <dt>

**ParentID**
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**key**](https://docs.microsoft.com/windows/desktop/WmiSdk/key-qualifier)
</dt> </dl>

</dd> <dt>

[RequirePlatformSecurityFeatures](https://docs.microsoft.com/windows/client-management/mdm/policy-csp-deviceguard#deviceguard-requireplatformsecurityfeatures)
</dt> <dd> <dl> <dt>

Data type: **sint32**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> </dl>

## Requirements



|                                     |                                                                                                |
|-------------------------------------|------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 10 \[desktop apps only\]<br/>                                                    |
| Minimum supported server<br/> | None supported<br/>                                                                      |
| Namespace<br/>                | Root\\cimv2\\mdm\\dmmap<br/>                                                             |
| MOF<br/>                      | <dl> <dt>DMWmiBridgeProv.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>DMWmiBridgeProv.dll</dt> </dl> |



 

 





