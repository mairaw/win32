---
Description: Automatically subclasses and adds 3D effects to all dialog boxes in the application.
ms.assetid: 96555052-c564-4cc7-9b24-e527f8e2f879
title: Ctl3dAutoSubclass function
ms.topic: article
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- Ctl3dAutoSubclass
api_type: 
- DllExport
api_location: 
- Ctl3d32.dll
---

# Ctl3dAutoSubclass function

Automatically subclasses and adds 3D effects to all dialog boxes in the application.

## Syntax


```C++
PUBLIC BOOL FAR PASCAL Ctl3dAutoSubclass(
   HANDLE hinstApp
);
```



## Parameters

<dl> <dt>

*hinstApp* 
</dt> <dd>

A handle to the application to be registered as a client.

</dd> </dl>

## Return value

Returns **TRUE** unless one of the following conditions exists, in which case it returns **FALSE**:

-   CTL3D is running under Windows version 3.0 or earlier.
-   CTL3D does not have space available in its tables for the current application. CTL3D can service up to 32 applications at the same time.
-   CTL3D cannot install its CBT hook.

## Remarks

This function has no associated import library or header file; you must call it using the [**LoadLibrary**](https://msdn.microsoft.com/en-us/library/ms684175(v=VS.85).aspx) and [**GetProcAddress**](https://msdn.microsoft.com/en-us/library/ms683212(v=VS.85).aspx) functions.

## Requirements



|                |                                                                                        |
|----------------|----------------------------------------------------------------------------------------|
| DLL<br/> | <dl> <dt>Ctl3d32.dll</dt> </dl> |



 

 




