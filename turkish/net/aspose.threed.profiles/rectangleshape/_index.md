---
title: RectangleShape
second_title: Aspose.3D for .NET API Referansı
description: Köşeleri yuvarlatılmış IFC uyumlu dikdörtgen şekil.
type: docs
weight: 1620
url: /tr/net/aspose.threed.profiles/rectangleshape/
---
## RectangleShape class

Köşeleri yuvarlatılmış IFC uyumlu dikdörtgen şekil.

```csharp
public class RectangleShape : ParameterizedProfile
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [RectangleShape](rectangleshape)() | Oluşturucusu[`RectangleShape`](../rectangleshape) |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Dışa aktarma sırasında bu varlığın hariç tutulup tutulmayacağını alır veya ayarlar. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Adı alır veya ayarlar. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | İlk üst düğümü alır veya ayarlar, eğer ilk üst düğüm ayarlanırsa bu varlık diğer üst düğümlerden ayrılır. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Tüm üst düğümleri alır, bir varlık geometri örneği için birden çok üst düğüme eklenebilir |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Tüm özelliklerin koleksiyonunu alır. |
| [RoundingRadius](../../aspose.threed.profiles/rectangleshape/roundingradius) { get; set; } | Derece olarak ölçülen dört köşenin de dairesel yaylarının yarıçapını alır veya ayarlar. Varsayılan değer 0.0 |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Bu nesnenin ait olduğu sahneyi alır |
| [XDim](../../aspose.threed.profiles/rectangleshape/xdim) { get; set; } | x-axis yönündeki dikdörtgenin kapsamını alır veya ayarlar_ Varsayılan değer 2.0 |
| [YDim](../../aspose.threed.profiles/rectangleshape/ydim) { get; set; } | Dikdörtgenin kapsamını y ekseni yönünde alır veya ayarlar Varsayılan değer 2.0 |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Özelliği bulur. Dinamik bir özellik olabilir (CreateDynamicProperty/SetProperty tarafından oluşturulmuştur) veya yerel özellik (adıyla tanımlanır) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Nesne uzayı koordinat sisteminde geçerli varlığın sınırlayıcı kutusunu alır. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey)() | Oluşturucuda kayıtlı varlık oluşturucunun anahtarını alır |
| override [GetExtent](../../aspose.threed.profiles/rectangleshape/getextent)() | Kapsamı x ve y boyutunda alır. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Belirtilen özelliğin değerini alın |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Dinamik bir özelliği kaldırır. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | name ile tanımlanan belirtilen özelliği kaldırın |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Belirtilen özelliğin değerini ayarlar |

### Ayrıca bakınız

* class [ParameterizedProfile](../parameterizedprofile)
* ad alanı [Aspose.ThreeD.Profiles](../../aspose.threed.profiles)
* toplantı [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
