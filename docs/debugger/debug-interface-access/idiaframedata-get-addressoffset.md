---
description: "Retrieves the offset part of the code address for the frame."
title: "IDiaFrameData::get_addressOffset"
ms.date: "11/04/2016"
ms.topic: "reference"
dev_langs:
  - "C++"
helpviewer_keywords:
  - "IDiaFrameData::get_addressOffset method"
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
---
# IDiaFrameData::get_addressOffset

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Retrieves the offset part of the code address for the frame.

## Syntax

```C++
HRESULT get_addressOffset ( 
   DWORD* pRetVal
);
```

#### Parameters
 `pRetVal`

[out] Returns the offset part of the code address for the frame.

## Return Value
 If successful, returns `S_OK`. Returns `S_FALSE` if this property is not supported. Otherwise, returns an error code.

## See also
- [IDiaFrameData](../../debugger/debug-interface-access/idiaframedata.md)
