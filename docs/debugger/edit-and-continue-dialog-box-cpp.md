---
title: "Edit and Continue Dialog Box (C++)"
description: Edit and Continue may report that it couldn't apply your code changes. Learn why this can happen and what you can do.
ms.date: "11/04/2016"
ms.topic: "ui-reference"
f1_keywords:
  - "vs.debug.ENC.failed.commit"
  - "vs.debug.ENC.failed.build"
dev_langs:
  - "CSharp"
  - "VB"
  - "FSharp"
  - "C++"
helpviewer_keywords:
  - "Edit and Continue, limitations"
  - "Failed to Apply Code Changes dialog box"
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
---
# Edit and Continue Dialog Box (C++)

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Edit and Continue could not apply the changes you made to your native code. This may be a temporary condition. Sometimes Edit and Continue cannot apply native code changes immediately, but can apply them later during the debugging session (for example, after completion of the current call to the procedure now executing). For more information, see [Edit and Continue](../debugger/edit-and-continue.md).

 You can edit the code to fix the error while still debugging, stop debugging and fix the code, or ignore the error and continue debugging. If you continue without making the fix, your code changes will not be applied immediately.

## See also
- [Edit and Continue, Debugging, Options Dialog Box](./edit-and-continue.md)