---
Description: Retrieves a type-information object, which can retrieve the type information for an interface.
ms.assetid: 2014485f-d937-415d-a2fc-0c69269b5237
title: CMediaControl.GetTypeInfo method
ms.topic: article
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- CMediaControl.GetTypeInfo
api_type: 
- COM
api_location: 
- Strmbase.lib
- Strmbase.dll
- Strmbasd.lib
- Strmbasd.dll
---

# CMediaControl.GetTypeInfo method

Retrieves a type-information object, which can retrieve the type information for an interface.

## Syntax


```C++
HRESULT GetTypeInfo(
   UINT      itinfo,
   LCID      lcid,
   ITypeInfo **pptinfo
);
```



## Parameters

<dl> <dt>

*itinfo* 
</dt> <dd>

Type information to return. Pass zero to retrieve type information for the **IDispatch** implementation.

</dd> <dt>

*lcid* 
</dt> <dd>

Locale ID for the type information. For classes that support localized member names, an object might be able to return different type information for different languages. For classes that do not support localized member names, this parameter can be ignored.

</dd> <dt>

*pptinfo* 
</dt> <dd>

Address of a pointer to the type-information object requested.

</dd> </dl>

## Return value

Returns an E\_POINTER if *pptinfo* is invalid. Returns TYPE\_E\_ELEMENTNOTFOUND if *itinfo* is not zero. Returns S\_OK if is successful. Otherwise, returns an **HRESULT** from one of the calls to retrieve the type.

## Requirements



|                    |                                                                                                                                                                                            |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Ctlutil.h (include Streams.h)</dt> </dl>                                                                                   |
| Library<br/> | <dl> <dt>Strmbase.lib (retail builds); </dt> <dt>Strmbasd.lib (debug builds)</dt> </dl> |



## See also

<dl> <dt>

[**CMediaControl Class**](cmediacontrol.md)
</dt> </dl>

 

 




