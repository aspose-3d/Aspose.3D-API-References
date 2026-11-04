---
title: "Clase PolygonBuilder"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Aspose.ThreeD.Entities.PolygonBuilder class. Una clase auxiliar para construir polígonos para Mesh"
type: docs
weight: 610
url: /es/net/aspose.threed.entities/polygonbuilder/
---
## PolygonBuilder class

Una clase auxiliar para construir polígonos para [`Mesh`](../mesh/)

```csharp
public sealed class PolygonBuilder
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PolygonBuilder](polygonbuilder/)(Mesh) | Inicializa una nueva instancia de la clase `PolygonBuilder`. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddVertex](../../aspose.threed.entities/polygonbuilder/addvertex/)(int) | Añade un índice de vértice al polígono |
| [Begin](../../aspose.threed.entities/polygonbuilder/begin/)() | Comienza a añadir un nuevo polígono |
| [End](../../aspose.threed.entities/polygonbuilder/end/)() | Finaliza la creación del polígono |

## Ejemplos

```csharp
Mesh mesh = new Mesh();
PolygonBuilder builder = new PolygonBuilder(mesh);
builder.Begin();
builder.AddVertex(0);
builder.AddVertex(1);
builder.AddVertex(2);
builder.End();
```

Igual a :

```csharp
Mesh mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

Si todos los índices están listos para usar, [`CreatePolygon`](../mesh/createpolygon/) es preferido, de lo contrario `PolygonBuilder` sería una mejor opción.

### Ver también

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


