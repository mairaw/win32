---
Description: Constructor method.
ms.assetid: e8e9138a-6c39-41de-a7f8-d9e9c4fe5ab6
title: CCritSec.CCritSec constructor
ms.topic: article
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- CCritSec.CCritSec
api_type: 
- COM
api_location: 
- Strmbase.lib
- Strmbase.dll
- Strmbasd.lib
- Strmbasd.dll
---

# CCritSec.CCritSec constructor

Constructor method.

## Syntax


```C++
CCritSec();
```



## Parameters

This constructor has no parameters.

## Remarks

This method calls the [**InitializeCriticalSection**](https://docs.microsoft.com/windows/desktop/api/synchapi/nf-synchapi-initializecriticalsection) function to initialize the critical section.

## Requirements



|                    |                                                                                                                                                                                            |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Wxutil.h (include Streams.h)</dt> </dl>                                                                                    |
| Library<br/> | <dl> <dt>Strmbase.lib (retail builds); </dt> <dt>Strmbasd.lib (debug builds)</dt> </dl> |



## See also

<dl> <dt>

[**CCritSec Class**](ccritsec.md)
</dt> </dl>

 

 




