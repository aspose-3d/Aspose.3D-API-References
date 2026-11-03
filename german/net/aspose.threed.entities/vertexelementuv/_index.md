---
title: "Klasse VertexElementUV"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.VertexElementUV Klasse. Definiert die UV-Koordinaten für angegebene Komponenten. Eine Geometrie kann mehrere VertexElementUV-Elemente besitzen und jedes hat unterschiedliche TextureMappings."
type: docs
weight: 960
url: /de/net/aspose.threed.entities/vertexelementuv/
---
## VertexElementUV class

Definiert die UV-Koordinaten für angegebene Komponenten. Eine Geometrie kann mehrere `VertexElementUV` Elemente enthalten, und jedes hat unterschiedliche [`TextureMapping`](../texturemapping/)s.

```csharp
public class VertexElementUV : VertexElementVector4
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [VertexElementUV](vertexelementuv/#constructor)() | Initialisiert eine neue Instanz der `VertexElementUV` Klasse. Der Standard-Texture-Mapping-Typ ist Diffuse |
| [VertexElementUV](vertexelementuv/#constructor_1)(TextureMapping) | Initialisiert eine neue Instanz der `VertexElementUV` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Data](../../aspose.threed.entities/vertexelementvector4/data/) { get; } | Gibt die Scheitelpunktdaten zurück |
| [Indices](../../aspose.threed.entities/vertexelement/indices/) { get; } | Gibt die Indexdaten zurück |
| [MappingMode](../../aspose.threed.entities/vertexelement/mappingmode/) { get; set; } | Liest oder setzt, wie das Element zugeordnet ist. |
| [Name](../../aspose.threed.entities/vertexelement/name/) { get; set; } | Liest oder setzt den Namen. |
| [ReferenceMode](../../aspose.threed.entities/vertexelement/referencemode/) { get; set; } | Liest oder setzt, wie das Element referenziert wird. |
| [VertexElementType](../../aspose.threed.entities/vertexelement/vertexelementtype/) { get; } | Liest den Typ des [`VertexElement`](../vertexelement/) |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddData](../../aspose.threed.entities/vertexelementuv/adddata/#adddata)(IEnumerable&lt;Vector2&gt;) |  |
| [AddData](../../aspose.threed.entities/vertexelementuv/adddata/#adddata_1)(IEnumerable&lt;Vector3&gt;) |  |
| override [Clear](../../aspose.threed.entities/vertexelementvector4/clear/)() | Entfernt alle Elemente aus den direkten und den Index-Arrays. |
| [CopyTo](../../aspose.threed.entities/vertexelementvector4/copyto/)(VertexElementVector4) | Kopiert Daten zum angegebenen Element |
| [SetData](../../aspose.threed.entities/vertexelementvector4/setdata/)(Vector4[]) | Daten laden |
| [SetIndices](../../aspose.threed.entities/vertexelement/setindices/)(int[]) | Indizes laden |
| override [ToString](../../aspose.threed.entities/vertexelement/tostring/)() | String-Darstellung des Vertex-Elements. |

### Siehe auch

* class [VertexElementVector4](../vertexelementvector4/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


