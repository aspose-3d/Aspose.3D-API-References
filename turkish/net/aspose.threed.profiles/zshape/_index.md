---
title: ZShape
second_title: Aspose.3D for .NET API Referansı
description: Parametrelerle tanımlanan IFC uyumlu Zşekilli profil.
type: docs
weight: 1660
url: /tr/net/aspose.threed.profiles/zshape/
---
## ZShape class

Parametrelerle tanımlanan IFC uyumlu Z-şekilli profil.

```csharp
public class ZShape : ParameterizedProfile
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ZShape](zshape)() | Oluşturucusu[`ZShape`](../zshape) |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Depth](../../aspose.threed.profiles/zshape/depth) { get; set; } | Web uzunluğunu alır veya ayarlar. |
| [EdgeRadius](../../aspose.threed.profiles/zshape/edgeradius) { get; set; } | Flanş kenarının yarıçapını alır veya ayarlar. |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Dışa aktarma sırasında bu varlığın hariç tutulup tutulmayacağını alır veya ayarlar. |
| [FilletRadius](../../aspose.threed.profiles/zshape/filletradius) { get; set; } | Flanş ve ağ arasındaki köşe yarıçapını alır veya ayarlar. |
| [FlangeThickness](../../aspose.threed.profiles/zshape/flangethickness) { get; set; } | Flanş kalınlığını alır veya ayarlar. |
| [FlangeWidth](../../aspose.threed.profiles/zshape/flangewidth) { get; set; } | Flanş uzunluğunu alır veya ayarlar. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Adı alır veya ayarlar. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | İlk üst düğümü alır veya ayarlar, eğer ilk üst düğüm ayarlanırsa bu varlık diğer üst düğümlerden ayrılır. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Tüm üst düğümleri alır, bir varlık geometri örneği için birden çok üst düğüme eklenebilir |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Tüm özelliklerin koleksiyonunu alır. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Bu nesnenin ait olduğu sahneyi alır |
| [WebThickness](../../aspose.threed.profiles/zshape/webthickness) { get; set; } | Duvarın kalınlığını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Özelliği bulur. Dinamik bir özellik olabilir (CreateDynamicProperty/SetProperty tarafından oluşturulmuştur) veya yerel özellik (adıyla tanımlanır) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Nesne uzayı koordinat sisteminde geçerli varlığın sınırlayıcı kutusunu alır. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey)() | Oluşturucuda kayıtlı varlık oluşturucunun anahtarını alır |
| override [GetExtent](../../aspose.threed.profiles/zshape/getextent)() | Kapsamı x ve y boyutunda alır. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Belirtilen özelliğin değerini alın |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Dinamik bir özelliği kaldırır. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | name ile tanımlanan belirtilen özelliği kaldırın |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Belirtilen özelliğin değerini ayarlar |

### Ayrıca bakınız

* class [ParameterizedProfile](../parameterizedprofile)
* ad alanı [Aspose.ThreeD.Profiles](../../aspose.threed.profiles)
* toplantı [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
