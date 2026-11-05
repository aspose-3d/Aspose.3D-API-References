---
title: "Mesh.op_BitwiseAnd"
second_title: "Aspose.3D for .NET API Referansı"
description: "Mesh yöntemi. İki ağın kesişimini hesaplar"
type: docs
weight: 130
url: /tr/net/aspose.threed.entities/mesh/op_bitwiseand/
---
## Mesh BitwiseAnd operator

İki ağın kesişimini hesapla

```csharp
public static Mesh operator &(Mesh a, Mesh b)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | Ağ | İlk ağ |
| b | Ağ | İkinci ağ |

### Dönüş Değeri

Sonuç ağı

## Örnekler

Aşağıdaki kod, iki ağın farkını nasıl hesaplayacağınızı gösterir:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
Mesh merged = box1 & box2;
```

### Ayrıca Bakınız

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


