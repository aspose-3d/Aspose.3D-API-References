---
title: "Mesh.Optimize"
second_title: "Aspose.3D for .NET API Referansı"
description: "Mesh yöntemi. Tekrarlanan kontrol noktalarını ortadan kaldırarak ağın bellek kullanımını optimize et"
type: docs
weight: 100
url: /tr/net/aspose.threed.entities/mesh/optimize/
---
## Optimize(bool) {#optimize}

Ağın bellek kullanımını tekrarlanan kontrol noktalarını ortadan kaldırarak optimize et

```csharp
public Mesh Optimize(bool vertexElements)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vertexElements | Boolean | Tekrarlanan vertex öğesi verilerini optimize et |

### Dönüş Değeri

Kompakt bellek kullanımıyla yeni ağ örneği

## Örnekler

Aşağıdaki kod, optimize edilmemiş bir ağdan tekrarlanan kontrol noktalarını nasıl ortadan kaldıracağınızı gösterir:

```csharp
//Sphere.ToMesh 117 kontrol noktası üretir
var mesh = (new Sphere()).ToMesh();
//Optimize edildikten sonra, sadece 86 kontrol noktası kalır, çokgen indeksleri de yeniden eşlenir.
var optimized = mesh.Optimize(true);
```

### Ayrıca Bakınız

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Optimize(bool, float, float, float) {#optimize_1}

Ağın bellek kullanımını tekrarlanan kontrol noktalarını ortadan kaldırarak optimize et

```csharp
public Mesh Optimize(bool vertexElements, float toleranceControlPoint = 1E-09, 
    float toleranceNormal = 1E-09, float toleranceUV = 1E-09)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vertexElements | Boolean | Tekrarlanan vertex öğesi verilerini optimize et |
| toleranceControlPoint | Single | Kontrol noktası toleransı, varsayılan değer 1e-9'dur |
| toleranceNormal | Single | Normal/tanjant/binormal toleransı, varsayılan değer 1e-9'dur |
| toleranceUV | Single | UV toleransı, varsayılan değer 1e-9'dur |

### Dönüş Değeri

Kompakt bellek kullanımıyla yeni ağ örneği

### Ayrıca Bakınız

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


