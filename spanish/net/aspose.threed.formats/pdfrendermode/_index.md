---
title: "Enum PdfRenderMode"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Enum Aspose.ThreeD.Formats.PdfRenderMode. El modo de renderizado especifica el estilo en que se representa la obra 3D"
type: docs
weight: 1410
url: /es/net/aspose.threed.formats/pdfrendermode/
---
## PdfRenderMode enumeration

El modo de renderizado especifica el estilo en que se renderiza el arte 3D.

```csharp
public enum PdfRenderMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Solid | `0` | Muestra formas geométricas texturizadas e iluminadas. |
| SolidWireframe | `1` | Muestra formas geométricas texturizadas e iluminadas (triángulos) con bordes de un solo color sobre ellas. |
| Transparent | `2` | Muestra formas geométricas texturizadas e iluminadas (triángulos) con un nivel adicional de transparencia. |
| TransparentWireframe | `3` | Muestra formas geométricas texturizadas e iluminadas (triángulos) con un nivel adicional de transparencia, con bordes opacos de un solo color sobre ellos. |
| BoundingBox | `4` | Muestra los bordes de la caja delimitadora de cada nodo, alineados con los ejes del espacio de coordenadas local de ese nodo. |
| TransparentBoundingBox | `5` | Muestra las caras de las cajas delimitadoras de cada nodo, alineadas con los ejes del espacio de coordenadas local de ese nodo, con un nivel adicional de transparencia. |
| TransparentBoundingBoxOutline | `6` | Muestra los bordes y caras de las cajas delimitadoras de cada nodo, alineados con los ejes del espacio de coordenadas local de ese nodo, con un nivel adicional de transparencia. |
| Wireframe | `7` | Muestra solo los bordes en un solo color. |
| ShadedWireframe | `8` | Muestra solo los bordes, aunque interpola su color entre sus dos vértices y aplica iluminación. |
| HiddenWireframe | `9` | Muestra los bordes en un solo color, aunque elimina los bordes orientados hacia atrás y los bordes ocultos. |
| Vertices | `10` | Muestra solo los vértices en un solo color. |
| ShadedVertices | `11` | Muestra solo los vértices, aunque usa su color de vértice y aplica iluminación. |
| Illustration | `12` | Muestra los bordes de silueta con superficies, elimina las líneas ocultas. |
| SolidOutline | `13` | Muestra los bordes de silueta con superficies iluminadas y texturizadas, elimina las líneas ocultas. |
| ShadedIllustration | `14` | Muestra los bordes de silueta con superficies iluminadas y texturizadas y un término emisivo adicional para eliminar áreas poco iluminadas de la obra. |

### Ver también

* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


