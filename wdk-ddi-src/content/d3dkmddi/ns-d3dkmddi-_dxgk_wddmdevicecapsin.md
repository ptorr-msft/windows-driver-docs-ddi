---
UID: NS:d3dkmddi._DXGK_WDDMDEVICECAPSIN
title: _DXGK_WDDMDEVICECAPSIN
description: Contains the WDDM version that is supported by the driver after the call to DxgkDdiAddDevice, and before the call to DxgkDdiStartDevice.
tech.root: display
ms.date: 04/04/2019
keywords: ["DXGK_WDDMDEVICECAPSIN structure"]
ms.keywords: _DXGK_WDDMDEVICECAPSIN, DXGK_WDDMDEVICECAPSIN,
req.header: d3dkmddi.h
req.include-header: 
req.target-type: 
req.target-min-winverclnt: Windows 10, version 1903
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.lib: 
req.dll: 
req.ddi-compliance: 
req.unicode-ansi: 
req.max-support: 
req.typenames: DXGK_WDDMDEVICECAPSIN
targetos: Windows
ms.custom: 19H1
f1_keywords:
 - _DXGK_WDDMDEVICECAPSIN
 - d3dkmddi/_DXGK_WDDMDEVICECAPSIN
 - DXGK_WDDMDEVICECAPSIN
 - d3dkmddi/DXGK_WDDMDEVICECAPSIN
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - d3dkmddi.h
api_name:
 - _DXGK_WDDMDEVICECAPSIN
 - DXGK_WDDMDEVICECAPSIN
product:
 - Windows
dev_langs:
 - c++
---

# _DXGK_WDDMDEVICECAPSIN structure


## -description

Contains the WDDM version that is supported by the driver after the call to [DxgkDdiAddDevice](../dispmprt/nc-dispmprt-dxgkddi_add_device.md), and before the call to [DxgkDdiStartDevice](../dispmprt/nc-dispmprt-dxgkddi_start_device.md).

## -struct-fields

### -field DxgkrnlInterfaceVersion

 
Indicates the version of the functional interface implemented by the display port driver. This value is the same value as the **Version member** of the [DXGKRNL_INTERFACE structure](../dispmprt/ns-dispmprt-_dxgkrnl_interface.md) that was passed to [DxgkDdiStartDevice](../dispmprt/nc-dispmprt-dxgkddi_start_device.md). 

See the [IS_OFFICIAL_DDI_INTERFACE_VERSION](../d3dukmdt/nf-d3dukmdt-is_official_ddi_interface_version.md) macro for a list of available values.

## -remarks

## -see-also

