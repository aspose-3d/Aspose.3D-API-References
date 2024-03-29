---
title: PolygonBuilder
second_title: Aspose.3D für .NET-API-Referenz
description: Eine Hilfsklasse zum Erstellen von PolygonenMesh./mesh
type: docs
weight: 550
url: /de/net/aspose.threed.entities/polygonbuilder/
---
## PolygonBuilder class

Eine Hilfsklasse zum Erstellen von Polygonen[`Mesh`](../mesh)

```csharp
public sealed class PolygonBuilder
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PolygonBuilder](polygonbuilder)(Mesh) | Initialisiert eine neue Instanz von[`PolygonBuilder`](../polygonbuilder) Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddVertex](../../aspose.threed.entities/polygonbuilder/addvertex)(int) | Fügt dem Polygon einen Scheitelpunktindex hinzu |
| [Begin](../../aspose.threed.entities/polygonbuilder/begin)() | Beginnt mit dem Hinzufügen eines neuen Polygons |
| [End](../../aspose.threed.entities/polygonbuilder/end)() | Beendet die Polygonerstellung |

### Beispiele

ist gleich : Wenn alle Indizes einsatzbereit sind,[`CreatePolygon`](../mesh/createpolygon) wird ansonsten bevorzugt[`PolygonBuilder`](../polygonbuilder) wäre die bessere Wahl.

```csharp
PolygonBuilder builder = new PolygonBuilder(mesh);
builder.Begin();
builder.AddVertex(0);
builder.AddVertex(1);
builder.AddVertex(2);
Builder.End();
```

```csharp
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### Siehe auch

* namensraum [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* Montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
