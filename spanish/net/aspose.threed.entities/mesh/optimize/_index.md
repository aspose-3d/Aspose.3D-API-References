---
title: "Mesh.Optimize"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Mesh. Optimiza el uso de memoria de la malla eliminando puntos de control duplicados"
type: docs
weight: 100
url: /es/net/aspose.threed.entities/mesh/optimize/
---
## Optimize(bool) {#optimize}

Optimiza el uso de memoria de la malla eliminando puntos de control duplicados

```csharp
public Mesh Optimize(bool vertexElements)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vertexElements | Boolean | Optimiza los datos de elementos de vértice duplicados |

### Valor de retorno

Nueva instancia de malla con uso de memoria compacto

## Ejemplos

El siguiente código muestra cómo eliminar puntos de control duplicados de una malla no optimizada:

```csharp
//Sphere.ToMesh genera 117 puntos de control
var mesh = (new Sphere()).ToMesh();
//Después de optimizar, solo hay 86 puntos de control, los índices de polígonos también se remapean.
var optimized = mesh.Optimize(true);
```

### Ver también

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Optimize(bool, float, float, float) {#optimize_1}

Optimiza el uso de memoria de la malla eliminando puntos de control duplicados

```csharp
public Mesh Optimize(bool vertexElements, float toleranceControlPoint = 1E-09, 
    float toleranceNormal = 1E-09, float toleranceUV = 1E-09)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vertexElements | Boolean | Optimiza los datos de elementos de vértice duplicados |
| toleranceControlPoint | Single | La tolerancia para el punto de control, el valor predeterminado es 1e-9 |
| toleranceNormal | Single | La tolerancia para normal/tangente/binormal, el valor predeterminado es 1e-9 |
| toleranceUV | Single | La tolerancia para uv, el valor predeterminado es 1e-9 |

### Valor de retorno

Nueva instancia de malla con uso de memoria compacto

### Ver también

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


