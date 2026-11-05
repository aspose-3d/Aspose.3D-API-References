---
title: "Mesh.Optimize"
second_title: "Aspose.3D för .NET API‑referens"
description: "Mesh metod. Optimera meshens minnesanvändning genom att eliminera duplicerade kontrollpunkter"
type: docs
weight: 100
url: /sv/net/aspose.threed.entities/mesh/optimize/
---
## Optimize(bool) {#optimize}

Optimera meshens minnesanvändning genom att eliminera duplicerade kontrollpunkter

```csharp
public Mesh Optimize(bool vertexElements)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vertexElements | Boolean | Optimera duplicerad vertex-elementdata |

### Returvärde

Ny mesh-instans med kompakt minnesanvändning

## Exempel

Följande kod visar hur man eliminerar duplicerade kontrollpunkter från en icke-optimerad mesh:

```csharp
//Sphere.ToMesh genererar 117 kontrollpunkter
var mesh = (new Sphere()).ToMesh();
//Efter optimering finns det bara 86 kontrollpunkter, polygonindex har också omkartlagts.
var optimized = mesh.Optimize(true);
```

### Se även

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Optimize(bool, float, float, float) {#optimize_1}

Optimera meshens minnesanvändning genom att eliminera duplicerade kontrollpunkter

```csharp
public Mesh Optimize(bool vertexElements, float toleranceControlPoint = 1E-09, 
    float toleranceNormal = 1E-09, float toleranceUV = 1E-09)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vertexElements | Boolean | Optimera duplicerad vertex-elementdata |
| toleranceControlPoint | Enkel | Toleransen för kontrollpunkt, standardvärdet är 1e-9 |
| toleranceNormal | Enkel | Toleransen för normal/tangent/binormal, standardvärdet är 1e-9 |
| toleranceUV | Enkel | Toleransen för uv, standardvärdet är 1e-9 |

### Returvärde

Ny mesh-instans med kompakt minnesanvändning

### Se även

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


