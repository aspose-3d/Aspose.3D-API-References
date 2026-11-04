---
title: "Enumeración MappingMode"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Aspose.ThreeD.Entities.MappingMode enum. Determina cómo se asigna el elemento a una superficie. El MappingMode define cómo se asigna VertexElement a la superficie de la geometría."
type: docs
weight: 500
url: /es/net/aspose.threed.entities/mappingmode/
---
## MappingMode enumeration

Determina cómo se asigna el elemento a una superficie. El `MappingMode` define cómo [`VertexElement`](../vertexelement/) se asigna a la superficie de la geometría.

```csharp
public enum MappingMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| ControlPoint | `0` | Cada dato se asigna al punto de control de la geometría. |
| PolygonVertex | `1` | El dato se asigna al vértice del polígono. Cuando un punto de control es compartido por varios polígonos, y el dato se asigna como PolygonVertex, el punto de control como vértice de diferentes polígonos tendrá sus propios datos. |
| Polygon | `2` | El dato se asigna al polígono. Cada vértice del polígono comparte el mismo dato cuando el modo de asignación es Polygon. |
| Edge | `3` | El dato se asigna al borde. Cada extremo del borde comparte el mismo dato cuando el modo de asignación es Edge. |
| AllSame | `4` | Un dato asignado a toda la superficie. Cualquier dato que se interprete como punto de control/vértice de polígono/extremos de arista, el dato siempre es el mismo que define AllSame. |

### Ver también

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


