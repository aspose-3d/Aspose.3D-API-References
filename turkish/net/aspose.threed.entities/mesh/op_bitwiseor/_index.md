---
title: "Mesh.op_BitwiseOr"
second_title: "Aspose.3D for .NET API Referansı"
description: "Mesh yöntemi. İki ağın birleşimini hesapla"
type: docs
weight: 140
url: /tr/net/aspose.threed.entities/mesh/op_bitwiseor/
---
## Mesh BitwiseOr operator

İki ağın birleşimini hesapla

```csharp
public static Mesh operator |(Mesh a, Mesh b)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | Ağ | İlk ağ |
| b | Ağ | İkinci ağ |

### Dönüş Değeri

Sonuç ağı

## Örnekler

Aşağıdaki kod, iki ağı birleştirerek tek bir ağ oluşturmanın nasıl yapılacağını gösterir:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
var merged = box1 | box2;
```

### Ayrıca Bakınız

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


