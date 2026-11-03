---
title: "Mesh.Optimize"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Mesh-Methode. Optimiert die Speichernutzung des Meshes, indem duplizierte Kontrollpunkte eliminiert werden."
type: docs
weight: 100
url: /de/net/aspose.threed.entities/mesh/optimize/
---
## Optimize(bool) {#optimize}

Optimiert die Speichernutzung des Meshes, indem duplizierte Kontrollpunkte entfernt werden

```csharp
public Mesh Optimize(bool vertexElements)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vertexElements | Boolean | Duplizierte Vertex-Elementdaten optimieren |

### Rückgabewert

Neue Mesh-Instanz mit kompaktem Speicherverbrauch

## Beispiele

Der folgende Code zeigt, wie duplizierte Kontrollpunkte aus einem nicht optimierten Mesh eliminiert werden:

```csharp
//Sphere.ToMesh erzeugt 117 Kontrollpunkte
var mesh = (new Sphere()).ToMesh();
//Nach der Optimierung gibt es nur noch 86 Kontrollpunkte, Polygonindizes werden ebenfalls neu zugeordnet.
var optimized = mesh.Optimize(true);
```

### Siehe auch

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Optimize(bool, float, float, float) {#optimize_1}

Optimiert die Speichernutzung des Meshes, indem duplizierte Kontrollpunkte entfernt werden

```csharp
public Mesh Optimize(bool vertexElements, float toleranceControlPoint = 1E-09, 
    float toleranceNormal = 1E-09, float toleranceUV = 1E-09)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vertexElements | Boolean | Duplizierte Vertex-Elementdaten optimieren |
| toleranceControlPoint | Single | Die Toleranz für Kontrollpunkte, Standardwert ist 1e-9 |
| toleranceNormal | Single | Die Toleranz für Normalen/Tangenten/Binormalen, Standardwert ist 1e-9 |
| toleranceUV | Single | Die Toleranz für UV, Standardwert ist 1e-9 |

### Rückgabewert

Neue Mesh-Instanz mit kompaktem Speicherverbrauch

### Siehe auch

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


