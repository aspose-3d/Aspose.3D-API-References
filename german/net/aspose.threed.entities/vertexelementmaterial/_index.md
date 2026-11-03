---
title: "Klasse VertexElementMaterial"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.VertexElementMaterial Klasse. Definiert den Materialindex für angegebene Komponenten. Ein Knoten kann mehrere Materialien haben; das VertexElementMaterial wird verwendet, um verschiedene Teile der Geometrie mit unterschiedlichen Materialien zu rendern."
type: docs
weight: 880
url: /de/net/aspose.threed.entities/vertexelementmaterial/
---
## VertexElementMaterial class

Definiert den Materialindex für angegebene Komponenten. Ein Knoten kann mehrere Materialien haben, das `VertexElementMaterial` wird verwendet, um verschiedene Teile der Geometrie mit unterschiedlichen Materialien zu rendern.

```csharp
public class VertexElementMaterial : VertexElement
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [VertexElementMaterial](vertexelementmaterial/)() | Initialisiert eine neue Instanz der `VertexElementMaterial` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Indices](../../aspose.threed.entities/vertexelement/indices/) { get; } | Gibt die Indexdaten zurück |
| [MappingMode](../../aspose.threed.entities/vertexelement/mappingmode/) { get; set; } | Liest oder setzt, wie das Element zugeordnet ist. |
| [Name](../../aspose.threed.entities/vertexelement/name/) { get; set; } | Liest oder setzt den Namen. |
| [ReferenceMode](../../aspose.threed.entities/vertexelement/referencemode/) { get; set; } | Liest oder setzt, wie das Element referenziert wird. |
| [VertexElementType](../../aspose.threed.entities/vertexelement/vertexelementtype/) { get; } | Liest den Typ des [`VertexElement`](../vertexelement/) |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clear](../../aspose.threed.entities/vertexelementmaterial/clear/)() | Entfernt alle Elemente aus den direkten und den Index-Arrays. |
| [SetIndices](../../aspose.threed.entities/vertexelement/setindices/)(int[]) | Indizes laden |
| override [ToString](../../aspose.threed.entities/vertexelement/tostring/)() | String-Darstellung des Vertex-Elements. |

## Beispiele

Der folgende Code zeigt, wie man unterschiedlichen Materialien verschiedenen Flächen einer Box zuweist.

```csharp
// Erstelle ein Mesh einer Box (eine Box besteht aus 6 Ebenen).
Mesh box = (new Box()).ToMesh();
// Erstelle ein Material-Element auf diesem Mesh.
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// Und gib für jede Ebene einen anderen Materialindex an.
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
```

### Siehe auch

* class [VertexElement](../vertexelement/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


