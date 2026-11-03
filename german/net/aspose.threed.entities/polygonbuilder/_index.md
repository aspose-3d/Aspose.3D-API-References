---
title: "Klasse PolygonBuilder"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.PolygonBuilder Klasse. Eine Hilfsklasse zum Erstellen von Polygonen für Mesh"
type: docs
weight: 610
url: /de/net/aspose.threed.entities/polygonbuilder/
---
## PolygonBuilder class

Eine Hilfsklasse zum Erstellen von Polygonen für [`Mesh`](../mesh/)

```csharp
public sealed class PolygonBuilder
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PolygonBuilder](polygonbuilder/)(Mesh) | Initialisiert eine neue Instanz der `PolygonBuilder`-Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddVertex](../../aspose.threed.entities/polygonbuilder/addvertex/)(int) | Fügt dem Polygon einen Scheitelindex hinzu |
| [Begin](../../aspose.threed.entities/polygonbuilder/begin/)() | Beginnt, ein neues Polygon hinzuzufügen |
| [End](../../aspose.threed.entities/polygonbuilder/end/)() | Beendet die Polygonerstellung |

## Beispiele

```csharp
Mesh mesh = new Mesh();
PolygonBuilder builder = new PolygonBuilder(mesh);
builder.Begin();
builder.AddVertex(0);
builder.AddVertex(1);
builder.AddVertex(2);
builder.End();
```

Gleich zu:

```csharp
Mesh mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

Wenn alle Indizes einsatzbereit sind, wird [`CreatePolygon`](../mesh/createpolygon/) bevorzugt, andernfalls wäre `PolygonBuilder` die bessere Wahl.

### Siehe auch

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


