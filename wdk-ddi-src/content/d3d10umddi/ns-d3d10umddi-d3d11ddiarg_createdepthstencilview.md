---
UID: NS:d3d10umddi.D3D11DDIARG_CREATEDEPTHSTENCILVIEW
title: D3D11DDIARG_CREATEDEPTHSTENCILVIEW (d3d10umddi.h)
description: The D3D11DDIARG_CREATEDEPTHSTENCILVIEW structure describes the depth-stencil view to create.
old-location: display\d3d11ddiarg_createdepthstencilview.htm
ms.date: 11/03/2022
ms.custom: content-health
keywords: ["D3D11DDIARG_CREATEDEPTHSTENCILVIEW structure"]
ms.keywords: D3D11DDIARG_CREATEDEPTHSTENCILVIEW, D3D11DDIARG_CREATEDEPTHSTENCILVIEW structure [Display Devices], UMDisplayDriver_Dx11param_Structs_17e6fa50-317c-445d-b304-8097f658652f.xml, d3d10umddi/D3D11DDIARG_CREATEDEPTHSTENCILVIEW, display.d3d11ddiarg_createdepthstencilview
req.header: d3d10umddi.h
req.include-header: D3d10umddi.h
req.target-type: Windows
req.target-min-winverclnt: Windows 7
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
tech.root: display
req.typenames: D3D11DDIARG_CREATEDEPTHSTENCILVIEW
f1_keywords:
 - D3D11DDIARG_CREATEDEPTHSTENCILVIEW
 - d3d10umddi/D3D11DDIARG_CREATEDEPTHSTENCILVIEW
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - d3d10umddi.h
api_name:
 - D3D11DDIARG_CREATEDEPTHSTENCILVIEW
---

# D3D11DDIARG_CREATEDEPTHSTENCILVIEW structure

## -description

The **D3D11DDIARG_CREATEDEPTHSTENCILVIEW** structure describes the depth-stencil view to create.

## -struct-fields

### -field hDrvResource [in]

A handle to the base depth stencil resource.

### -field Format [in]

A DXGI_FORMAT-typed value that indicates the pixel format of the depth-stencil view.

### -field ResourceDimension [in]

A [**D3D10DDIRESOURCE_TYPE**](/windows-hardware/drivers/display/ne-d3d10umddi-d3d10ddiresource_type)-typed value that indicates the resource type and dimensionality of the base resource.

### -field Flags [in]

A valid bitwise OR of [**D3D11_DDI_CREATEDEPTHSTENCILVIEW_FLAG**](ne-d3d10umddi-d3d11_ddi_createdepthstencilview_flag.md)-typed values that indicates the type of depth-stencil view to create.

### -field Tex1D [in]

If the value in the **ResourceDimension** member is set to D3D10DDIRESOURCE_TEXTURE1D, a member in the union that is contained in D3D10DDIARG_CREATEDEPTHSTENCILVIEW that can hold a [**D3D10DDIARG_TEX1D_DEPTHSTENCILVIEW**](ns-d3d10umddi-d3d10ddiarg_tex1d_depthstencilview.md) structure for a one-dimensional texture.

### -field Tex2D [in]

If the value in the **ResourceDimension** member is set to D3D10DDIRESOURCE_TEXTURE2D, a member in the union that is contained in D3D10DDIARG_CREATEDEPTHSTENCILVIEW that can hold a [**D3D10DDIARG_TEX2D_DEPTHSTENCILVIEW**](ns-d3d10umddi-d3d10ddiarg_tex2d_depthstencilview.md) structure for a two-dimensional texture.

### -field TexCube [in]

If the value in the **ResourceDimension** member is set to D3D10DDIRESOURCE_TEXTURECUBE, a member in the union that is contained in D3D10DDIARG_CREATEDEPTHSTENCILVIEW that can hold a [**D3D10DDIARG_TEXCUBE_DEPTHSTENCILVIEW**](ns-d3d10umddi-d3d10ddiarg_texcube_depthstencilview.md) structure for a cube texture.

## -see-also

[**CalcPrivateDepthStencilViewSize(D3D11)**](nc-d3d10umddi-pfnd3d11ddi_calcprivatedepthstencilviewsize.md)

[**CreateDepthStencilView(D3D11)**](nc-d3d10umddi-pfnd3d11ddi_createdepthstencilview.md)

[**D3D10DDIARG_TEX1D_DEPTHSTENCILVIEW**](ns-d3d10umddi-d3d10ddiarg_tex1d_depthstencilview.md)

[**D3D10DDIARG_TEX2D_DEPTHSTENCILVIEW**](ns-d3d10umddi-d3d10ddiarg_tex2d_depthstencilview.md)

[**D3D10DDIARG_TEXCUBE_DEPTHSTENCILVIEW**](ns-d3d10umddi-d3d10ddiarg_texcube_depthstencilview.md)

[**D3D10DDIRESOURCE_TYPE**](/windows-hardware/drivers/display/ne-d3d10umddi-d3d10ddiresource_type)

[**D3D11_DDI_CREATEDEPTHSTENCILVIEW_FLAG**](ne-d3d10umddi-d3d11_ddi_createdepthstencilview_flag.md)
