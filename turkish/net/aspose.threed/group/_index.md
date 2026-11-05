---
title: "Sınıf Group"
second_title: "Aspose.3D for .NET API Referansı"
description: "Aspose.ThreeD.Group sınıfı. Bir Grup, Node'un mantıksal ilişkilerini temsil eder"
type: docs
weight: 1570
url: /tr/net/aspose.threed/group/
---
## Group class

Bir `Group` [`Node`](../node/) öğesinin mantıksal ilişkilerini temsil eder.

```csharp
public class Group : A3DObject
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Group](group/)(string) | Yeni bir `Group` örneği oluştur |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Groups](../../aspose.threed/group/groups/) { get; } | Alt gruplar |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Adı alır veya ayarlar. |
| [Nodes](../../aspose.threed/group/nodes/) { get; } | Bu gruptaki düğümler |
| [Parent](../../aspose.threed/group/parent/) { get; } | Mevcut grubun üst grup |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Tüm özelliklerin koleksiyonunu alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Özelliği bulur. Dinamik bir özellik (CreateDynamicProperty/SetProperty ile oluşturulan) veya yerel özellik (adıyla tanımlanan) olabilir. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Belirtilen özelliğin değerini al. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Dinamik bir özelliği kaldırır. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Adı ile tanımlanan belirtilen özelliği kaldır. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Belirtilen özelliğin değerini ayarlar. |
| override [ToString](../../aspose.threed/group/tostring/)() | `Group`'un string temsilini alır |

### Ayrıca Bakınız

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


