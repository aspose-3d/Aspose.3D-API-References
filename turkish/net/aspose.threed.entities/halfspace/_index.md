---
title: "Sınıf HalfSpace"
second_title: "Aspose.3D for .NET API Referansı"
description: "Aspose.ThreeD.Entities.HalfSpace sınıf. HalfSpace, bir düzlem tarafından bölünmüş sonsuz bir uzayı temsil eder; bu, BooleanOperator ile kullanılabilir."
type: docs
weight: 420
url: /tr/net/aspose.threed.entities/halfspace/
---
## HalfSpace class

`HalfSpace` bir düzlem tarafından bölünmüş sonsuz bir uzayı temsil eder, bu [`BooleanOperator`](../booleanoperator/) ile kullanılabilir.

```csharp
public class HalfSpace : Entity
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [HalfSpace](halfspace/#constructor)() | `HalfSpace`'in yeni bir örneğini oluşturur |
| [HalfSpace](halfspace/#constructor_1)(Vector3, Vector3) | Verilen normal vektör ve kesici düzlem üzerindeki bir konumla `HalfSpace`'in yeni bir örneğini oluşturur; |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Dışa aktarım sırasında bu varlığın dışlanıp dışlanmayacağını alır veya ayarlar. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Adı alır veya ayarlar. |
| [Normal](../../aspose.threed.entities/halfspace/normal/) { get; set; } | Bölünmüş düzlemin normali, düzlem N * P + D = 0 olarak tanımlanır; burada N Normal ve P düzlem üzerindeki herhangi bir noktadır. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | İlk üst düğümü alır veya ayarlar, ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir. |
| [Position](../../aspose.threed.entities/halfspace/position/) { get; set; } | Herhangi bir nokta bölünmüş düzlemde, düzlem N * P + D = 0 olarak tanımlanır; burada N Normal ve P düzlemdeki herhangi bir noktadır. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Tüm özelliklerin koleksiyonunu alır. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Bu nesnenin ait olduğu sahneyi alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Özelliği bulur. Dinamik bir özellik (CreateDynamicProperty/SetProperty ile oluşturulan) veya yerel özellik (adıyla tanımlanan) olabilir. |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Renderer içinde kayıtlı varlık işleyicisinin anahtarını alır. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Belirtilen özelliğin değerini al. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Dinamik bir özelliği kaldırır. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Adı ile tanımlanan belirtilen özelliği kaldır. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Belirtilen özelliğin değerini ayarlar. |

### Ayrıca Bakınız

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


