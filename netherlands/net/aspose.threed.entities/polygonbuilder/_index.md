---
title: PolygonBuilder
second_title: Aspose.3D voor .NET API-referentie
description: Een hulpklasse om polygoon voor te bouwenMesh./mesh/
type: docs
weight: 550
url: /nl/net/aspose.threed.entities/polygonbuilder/
---
## PolygonBuilder class

Een hulpklasse om polygoon voor te bouwen[`Mesh`](../mesh/)

```csharp
public sealed class PolygonBuilder
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [PolygonBuilder](polygonbuilder/)(Mesh) | Initialiseert een nieuw exemplaar van het`PolygonBuilder` klasse. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddVertex](../../aspose.threed.entities/polygonbuilder/addvertex/)(int) | Voegt een hoekpuntindex toe aan de polygoon |
| [Begin](../../aspose.threed.entities/polygonbuilder/begin/)() | Begint een nieuwe polygoon toe te voegen |
| [End](../../aspose.threed.entities/polygonbuilder/end/)() | Voltooit het maken van de polygoon |

### Voorbeelden

Gelijk aan : Als alle indexen klaar zijn voor gebruik,[`CreatePolygon`](../mesh/createpolygon/) heeft de voorkeur, anders`PolygonBuilder` zou een betere keuze zijn.

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

### Zie ook

* naamruimte [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
