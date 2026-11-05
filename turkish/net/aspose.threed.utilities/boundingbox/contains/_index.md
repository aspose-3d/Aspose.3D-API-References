---
title: "BoundingBox.Contains"
second_title: "Aspose.3D for .NET API Referansı"
description: "BoundingBox yöntemi. p noktasının sınırlama kutusunun içinde olup olmadığını kontrol edin"
type: docs
weight: 100
url: /tr/net/aspose.threed.utilities/boundingbox/contains/
---
## Contains(Vector3) {#contains_1}

p noktasının sınırlama kutusunun içinde olup olmadığını kontrol edin

```csharp
public bool Contains(Vector3 p)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| p | Vector3 | Test edilecek nokta |

### Dönüş Değeri

Nokta sınırlama kutusunun içinde ise doğru.

## Örnekler

Aşağıdaki kod, bir noktanın sınırlama kutusunun içinde olup olmadığını nasıl kontrol edeceğini gösterir.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var pt = new Vector3(4, 4, 4);
Console.WriteLine("Bounding box overlaps = " + boundingBox.Contains(pt));
```

### Ayrıca Bakınız

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Contains(BoundingBox) {#contains}

Mevcut sınırlama kutusunun içinde olup olmadığını kontrol etmek için sınırlama kutusu.

```csharp
public bool Contains(BoundingBox bbox)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bbox | BoundingBox |  |

### Ayrıca Bakınız

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


