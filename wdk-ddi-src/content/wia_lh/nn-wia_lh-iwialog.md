---
UID: NN:wia_lh.IWiaLog
title: IWiaLog (wia_lh.h)
description: The IWiaLog interface is obsolete and is no longer supported. Use the Diagnostic Log Macros instead.
tech.root: image
ms.date: 11/10/2022
keywords: ["IWiaLog interface"]
ms.keywords: IWiaLog, IWiaLog interface [Imaging Devices], IWiaLog interface [Imaging Devices],described, IWiaLog_0284e394-6bc5-40b8-8174-0041bfc0d5dd.xml, image.iwialog_interface, wia_lh/IWiaLog
req.header: wia_lh.h
req.include-header: Wia_lh.h
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
f1_keywords:
 - IWiaLog
 - wia_lh/IWiaLog
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - wia_lh.h
api_name:
 - IWiaLog
---

## -description

> [!IMPORTANT]
> The **IWiaLog** interface is obsolete and is no longer supported. Use the [**Diagnostic Log Macros**](/windows-hardware/drivers/image/wia-diagnostic-log-macros) instead.

The **IWiaLog** interface provides methods to enable minidrivers to log trace, error, and warning messages to the diagnostic log file Wiaservc.log.

The diagnostic log file *Wiaservc.log* is found in the Windows directory, or in the directory returned by the [GetWindowsDirectory](/windows/win32/api/sysinfoapi/nf-sysinfoapi-getwindowsdirectorya) system API call.

## -inheritance
