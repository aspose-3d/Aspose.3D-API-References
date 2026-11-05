---
title: "BoundingBox.OverlapsWith"
second_title: "Aspose.3D for .NET API Referansı"
description: "BoundingBox metodu. Geçerli sınırlama kutusunun belirtilen sınırlama kutusuyla çakışıp çakışmadığını kontrol eder"
type: docs
weight: 140
url: /tr/net/aspose.threed.utilities/boundingbox/overlapswith/
---
## BoundingBox.OverlapsWith method

Geçerli sınırlama kutusunun belirtilen sınırlama kutusuyla çakışıp çakışmadığını kontrol eder.

```csharp
public bool OverlapsWith(BoundingBox box)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kutu | BoundingBox | Test edilecek diğer sınırlama kutusu |

### Dönüş Değeri

Mevcut sınırlama kutusu verilenle çakışıyorsa doğru.

## Örnekler

Aşağıdaki kod, iki sınırlama kutusunun birbirleriyle çakışıp çakışmadığını nasıl kontrol edeceğini gösterir.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
Console.WriteLine("Bounding box overlaps = " + boundingBox.OverlapsWith(bbox2));
```

### Ayrıca Bakınız

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


