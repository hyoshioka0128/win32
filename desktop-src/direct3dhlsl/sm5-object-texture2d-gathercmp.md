---
title: GatherCmp(S,float,float,int) function
description: Samples a texture, tests the samples against a compare value, and returns all four components.
ms.assetid: 1084bcb3-2834-400a-98ff-4e3182f63f20
keywords:
- GatherCmp function HLSL
topic_type:
- apiref
api_name:
- GatherCmp
api_type:
- NA
ms.topic: article
ms.date: 05/31/2018
api_location: 
---

# GatherCmp(S,float,float,int) function

Samples a texture, tests the samples against a compare value, and returns all four components.

## Syntax

``` syntax
float4 GatherCmp(
  in SamplerComparisonState s,
  in float2 location,
  in float compare_value,
  in int2 offset
);
```

## Parameters

<dl> <dt>

*s* \[in\]
</dt> <dd>

Type: **SamplerComparisonState**

The zero-based sampler index.

</dd> <dt>

*location* \[in\]
</dt> <dd>

Type: **float2**

The sample coordinates (u,v).

</dd> <dt>

*compare\_value* \[in\]
</dt> <dd>

Type: **float**

A value to compare each against each sampled value.

</dd> <dt>

*offset* \[in\]
</dt> <dd>

Type: **int2**

An offset that is applied to the texture coordinate before sampling.

</dd> </dl>

## Return value

Type: **float4**

A four-component value, each component is the result of a per-component comparison.

## Remarks

The texture samples can be used for bilinear interpolation.

This function is supported for the following types of shaders:



| Vertex | Hull | Domain | Geometry | Pixel | Compute |
|--------|------|--------|----------|-------|---------|
| x      | x    | x      | x        | x     | x       |



 

## See also

<dl> <dt>

[GatherCmp methods](texture2d-gathercmp.md)
</dt> <dt>

[Shader Model 5](d3d11-graphics-reference-sm5.md)
</dt> </dl>

 

 




