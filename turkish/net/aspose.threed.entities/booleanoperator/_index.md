---
title: "BooleanOperator sınıfı"
second_title: "Aspose.3D for .NET API Referansı"
description: "Aspose.ThreeD.Entities.BooleanOperator sınıfı. Boolean operatör, iki **IMeshConvertible** örneğine Boolean işlemi uygulamanıza olanak tanır."
type: docs
weight: 280
url: /tr/net/aspose.threed.entities/booleanoperator/
---
## BooleanOperator class

Boolean operatör, iki [`IMeshConvertible`](../imeshconvertible/) örneğine Boolean işlemi uygulamanıza olanak tanır.

```csharp
public class BooleanOperator : Entity, IMeshConvertible
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [BooleanOperator](booleanoperator/#constructor)() | `BooleanOperator` yapıcı |
| [BooleanOperator](booleanoperator/#constructor_1)(BooleanOperation, A3DObject, A3DObject) | `BooleanOperator`'ın iki operand ile yeni bir örneğini oluşturur |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Dışa aktarım sırasında bu varlığın dışlanıp dışlanmayacağını alır veya ayarlar. |
| [First](../../aspose.threed.entities/booleanoperator/first/) { get; set; } | Boolean operatörünün birinci operandı |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Adı alır veya ayarlar. |
| [Operator](../../aspose.threed.entities/booleanoperator/operator/) { get; set; } | Sonuç mesh'ini oluşturmak için işlemde kullanılan Boolean operatörü. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | İlk üst düğümü alır veya ayarlar, ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Tüm özelliklerin koleksiyonunu alır. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Bu nesnenin ait olduğu sahneyi alır. |
| [Second](../../aspose.threed.entities/booleanoperator/second/) { get; set; } | Boolean operatörünün ikinci operandı |

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
| [ToMesh](../../aspose.threed.entities/booleanoperator/tomesh/)() | İki operand üzerinde Boolean işlemini gerçekleştir. |

### Ayrıca Bakınız

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


