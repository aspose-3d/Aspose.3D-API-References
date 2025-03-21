---
title: Class PolygonBuilder
second_title: Aspose.3D for .NET API Reference
description: Aspose.ThreeD.Entities.PolygonBuilder class. A helper class to build polygon for Mesh
type: docs
weight: 580
url: /net/aspose.threed.entities/polygonbuilder/
---
## PolygonBuilder class

A helper class to build polygon for [`Mesh`](../mesh/)

```csharp
public sealed class PolygonBuilder
```

## Constructors

| Name | Description |
| --- | --- |
| [PolygonBuilder](polygonbuilder/)(Mesh) | Initializes a new instance of the `PolygonBuilder` class. |

## Methods

| Name | Description |
| --- | --- |
| [AddVertex](../../aspose.threed.entities/polygonbuilder/addvertex/)(int) | Adds a vertex index to the polygon |
| [Begin](../../aspose.threed.entities/polygonbuilder/begin/)() | Begins to add a new polygon |
| [End](../../aspose.threed.entities/polygonbuilder/end/)() | Finishes the polygon creation |

## Examples

```csharp
Mesh mesh = new Mesh();
PolygonBuilder builder = new PolygonBuilder(mesh);
builder.Begin();
builder.AddVertex(0);
builder.AddVertex(1);
builder.AddVertex(2);
builder.End();
```

Equals to :

```csharp
Mesh mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

If all indices are ready to use, [`CreatePolygon`](../mesh/createpolygon/) is preferred, otherwise `PolygonBuilder` would be a better choice.

### See Also

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


