---
title: "Mesh.Optimize"
second_title: "Aspose.3D voor .NET API-referentie"
description: "Mesh‑methode. Optimaliseer het geheugenverbruik van de meshs door dubbele controlepunten te verwijderen"
type: docs
weight: 100
url: /nl/net/aspose.threed.entities/mesh/optimize/
---
## Optimize(bool) {#optimize}

Optimaliseer het geheugenverbruik van de mesh door dubbele controlepunten te verwijderen

```csharp
public Mesh Optimize(bool vertexElements)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vertexElements | Boolean | Optimaliseer gedupliceerde vertex-elementgegevens |

### Retourwaarde

Nieuwe mesh-instantie met compact geheugenverbruik

## Voorbeelden

De volgende code laat zien hoe gedupliceerde controlepunten uit een niet-geoptimaliseerde mesh kunnen worden verwijderd:

```csharp
//Sphere.ToMesh genereert 117 controlepunten
var mesh = (new Sphere()).ToMesh();
//Na optimalisatie zijn er slechts 86 controlepunten, polygonindices zijn ook opnieuw gemapt.
var optimized = mesh.Optimize(true);
```

### Zie ook

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Optimize(bool, float, float, float) {#optimize_1}

Optimaliseer het geheugenverbruik van de mesh door dubbele controlepunten te verwijderen

```csharp
public Mesh Optimize(bool vertexElements, float toleranceControlPoint = 1E-09, 
    float toleranceNormal = 1E-09, float toleranceUV = 1E-09)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vertexElements | Boolean | Optimaliseer gedupliceerde vertex-elementgegevens |
| toleranceControlPoint | Enkel | De tolerantie voor controlepunt, standaardwaarde is 1e-9 |
| toleranceNormal | Enkel | De tolerantie voor normaal/tangent/binormaal, standaardwaarde is 1e-9 |
| toleranceUV | Enkel | De tolerantie voor uv, standaardwaarde is 1e-9 |

### Retourwaarde

Nieuwe mesh-instantie met compact geheugenverbruik

### Zie ook

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


