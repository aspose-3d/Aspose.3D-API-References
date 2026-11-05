---
title: "Sınıf CenterLineProfile"
second_title: "Aspose.3D for .NET API Referansı"
description: "Aspose.ThreeD.Profiles.CenterLineProfile sınıfı. IFC uyumlu merkez hat profili"
type: docs
weight: 1690
url: /tr/net/aspose.threed.profiles/centerlineprofile/
---
## CenterLineProfile class

IFC uyumlu merkez hat profili

```csharp
public class CenterLineProfile : Profile
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [CenterLineProfile](centerlineprofile/)(Curve, double) | Belirtilen eğriyi merkez hat olarak kullanarak yeni bir `CenterLineProfile` oluşturur. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Curve](../../aspose.threed.profiles/centerlineprofile/curve/) { get; set; } | Profilin merkez hat eğrisi |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Dışa aktarım sırasında bu varlığın dışlanıp dışlanmayacağını alır veya ayarlar. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Adı alır veya ayarlar. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | İlk üst düğümü alır veya ayarlar, ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Tüm özelliklerin koleksiyonunu alır. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Bu nesnenin ait olduğu sahneyi alır. |
| [Thickness](../../aspose.threed.profiles/centerlineprofile/thickness/) { get; set; } | Merkez hat boyunca uygulanan kalınlık |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Özelliği bulur. Dinamik bir özellik (CreateDynamicProperty/SetProperty ile oluşturulan) veya yerel özellik (adıyla tanımlanan) olabilir. |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Renderer içinde kayıtlı varlık işleyicisinin anahtarını alır. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Belirtilen özelliğin değerini al. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Dinamik bir özelliği kaldırır. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Adı ile tanımlanan belirtilen özelliği kaldır. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Belirtilen özelliğin değerini ayarlar. |

### Ayrıca Bakınız

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


