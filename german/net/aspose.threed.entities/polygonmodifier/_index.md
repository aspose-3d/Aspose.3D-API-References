---
title: "Klasse PolygonModifier"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.PolygonModifier Klasse. Werkzeuge zum Ändern von Polygonen"
type: docs
weight: 620
url: /de/net/aspose.threed.entities/polygonmodifier/
---
## PolygonModifier class

Hilfsprogramme zum Ändern von Polygonen

```csharp
public class PolygonModifier
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [ApplyTransform](../../aspose.threed.entities/polygonmodifier/applytransform/)(Node, Matrix4) | Transformationsmatrix auf die Kontrollpunkte aller Geometrien anwenden |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal/#buildtangentbinormal)(Mesh) | Dies erzeugt Tangenten und Binormale im Mesh. Normalen sind erforderlich; wenn keine Normalen im Mesh vorhanden sind, werden die Normaldaten aus der Position erstellt. UVs sind ebenfalls erforderlich, es wird eine Ausnahme ausgelöst, wenn keine UV gefunden wird. |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal/#buildtangentbinormal_1)(Scene) | Dies erzeugt Tangenten und Binormale für alle Meshes der Szene. Normalen sind erforderlich; wenn keine Normalen im Mesh vorhanden sind, werden die Normaldaten aus der Position erstellt. UVs sind ebenfalls erforderlich, das Mesh wird ignoriert, wenn keine UV definiert ist. |
| static [GenerateNormal](../../aspose.threed.entities/polygonmodifier/generatenormal/)(Mesh) | Normaldaten aus Mesh-Definition generieren |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv/#generateuv)(Mesh) | UV-Daten aus dem angegebenen Eingabe-Mesh generieren |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv/#generateuv_1)(Mesh, VertexElementNormal) | UV-Daten aus dem angegebenen Eingabe-Mesh und den spezifizierten Normaldaten generieren. |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh_2)(IList&lt;Node&gt;) |  |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh)(Node) | Einen gesamten Knoten in ein einzelnes transformiertes Mesh konvertieren. Vertex-Elemente wie Normalen-/Texturkoordinaten werden noch nicht unterstützt. |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh_1)(Scene) | Eine gesamte Szene in ein einzelnes transformiertes Mesh konvertieren. Vertex-Elemente wie Normalen-/Texturkoordinaten werden noch nicht unterstützt. |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale/#scale_1)(Node, Vector3) | Alle Geometrien in diesem Knoten skalieren (die Kontrollpunkte skalieren, nicht die Transformationsmatrix). |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale/#scale)(Scene, Vector3) | Alle Geometrien in dieser Szene skalieren (die Kontrollpunkte skalieren, nicht die Transformationsmatrix). |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh)(Mesh, SplitMeshPolicy) | Mesh in Teil-Meshes aufteilen mittels [`VertexElementMaterial`](../vertexelementmaterial/). Jeder Teil-Mesh verwendet nur ein Material. Das ursprüngliche Mesh wird nicht verändert. |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh_2)(Scene, SplitMeshPolicy, bool) | Mesh in Teil-Meshes aufteilen mittels [`VertexElementMaterial`](../vertexelementmaterial/). Jeder Teil-Mesh verwendet nur ein Material. Mesh-Aufteilung auf allen Knoten der Szene durchführen. |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh_1)(Node, SplitMeshPolicy, bool, bool) | Mesh in Teil-Meshes aufteilen mittels [`VertexElementMaterial`](../vertexelementmaterial/). Jeder Teil-Mesh verwendet nur ein Material. Mesh-Aufteilung an einem Knoten durchführen. |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_1)(IList&lt;Vector4&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate)(Mesh) | Ein polygonbasiertes Mesh in ein vollständiges Dreiecks-Mesh konvertieren |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_5)(Scene) | Alle polygonbasierten Meshes in ein vollständiges Dreiecks-Mesh konvertieren |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_3)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_2)(IList&lt;Vector4&gt;, int[]) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_4)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;, bool, out Vector3[]) |  |

### Siehe auch

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


