---
Description: User-user information is a buffer that can be transmitted from one end of a connection to another. This information is specific to the ISDN Q.931 standard. Please refer to your service providers documentation on the meaning and use of this data.
ms.assetid: 7040ab51-184e-4ffc-9333-b82ae5a5a7f3
title: User-user information
ms.topic: article
ms.date: 05/31/2018
---

# User-user information

User-user information is a buffer that can be transmitted from one end of a connection to another. This information is specific to the ISDN Q.931 standard. Please refer to your service provider's documentation on the meaning and use of this data.

Not all service providers support use of this information.

**TAPI 2.x:  **[**lineGetCallInfo**](https://msdn.microsoft.com/en-us/library/ms735720(v=VS.85).aspx), **dwCallDataSize** and **dwCallDataOffset** members of [**LINECALLINFO**](https://msdn.microsoft.com/en-us/library/ms735527(v=VS.85).aspx), [**lineSendUserUserInfo**](https://msdn.microsoft.com/en-us/library/ms736067(v=VS.85).aspx)

**TAPI 3.x:  **[**ITCallInfo::GetCallInfoBuffer**](/windows/desktop/api/tapi3if/nf-tapi3if-itcallinfo-getcallinfobuffer), called with the **CIB\_USERUSERINFO** member of [**CALLINFO\_BUFFER**](/windows/desktop/api/Tapi3if/ne-tapi3if-callinfo_buffer), [**ITCallInfo::ReleaseUserUserInfo**](/windows/desktop/api/tapi3if/nf-tapi3if-itcallinfo-releaseuseruserinfo)

 

 



