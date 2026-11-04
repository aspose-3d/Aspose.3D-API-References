---
title: "BoundingBox.FromGeometry"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método BoundingBox. Construye un cuadro delimitador a partir de la geometría dada"
type: docs
weight: 40
url: /es/net/aspose.threed.utilities/boundingbox/fromgeometry/
---
## BoundingBox.FromGeometry method

Construir una caja delimitadora a partir de la geometría dada

```csharp
public static BoundingBox FromGeometry(Geometry geometry)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| geometría | Geometría | La geometría para calcular la caja delimitadora |

### Valor de retorno

La caja delimitadora de la geometría dada

## Ejemplos

El siguiente código muestra cómo construir una caja delimitadora a partir de una instancia de geometría.

```csharp
var sphere = (new Sphere()).ToMesh();
var boundingBox = BoundingBox.FromGeometry(sphere);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Ver también

* class [Geometry](../../../aspose.threed.entities/geometry/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


