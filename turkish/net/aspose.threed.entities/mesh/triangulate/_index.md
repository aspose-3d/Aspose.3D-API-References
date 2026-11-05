---
title: "Mesh.Triangulate"
second_title: "Aspose.3D for .NET API Referansı"
description: "Mesh yöntemi. Üçgenleştirilmiş ağı döndür"
type: docs
weight: 120
url: /tr/net/aspose.threed.entities/mesh/triangulate/
---
## Mesh.Triangulate method

Üçgenleştirilmiş ağı döndür

```csharp
public Mesh Triangulate()
```

### Dönüş Değeri

Mevcut ağ, eğer zaten üçgenleştirilmişse, aksi takdirde yeni bir üçgenleştirilmiş ağ hesaplanıp döndürülecek

## Örnekler

Aşağıdaki kod, bir ağı nasıl üçgenleştireceğinizi gösterir:

```csharp
//Düzlem ağı sadece 4 kontrol noktasına sahip bir çokgen içerir
var mesh = (new Plane()).ToMesh();
//Üçgenleştirildikten sonra, yeni ağın dikdörtgeni 2 üçgene dönüşecek.
var triangulated = mesh.Triangulate();
```

### Ayrıca Bakınız

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


