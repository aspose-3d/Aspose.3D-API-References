---
title: "PolygonModifier.SplitMesh"
second_title: "Aspose.3D für .NET API-Referenz"
description: "PolygonModifier-Methode. Mesh in Submeshes nach VertexElementMaterial aufteilen. Jeder Submesh verwendet nur ein Material. Mesh-Aufteilung an einem Knoten durchführen."
type: docs
weight: 70
url: /de/net/aspose.threed.entities/polygonmodifier/splitmesh/
---
## SplitMesh(Node, SplitMeshPolicy, bool, bool) {#splitmesh_1}

Mesh in Sub-Meshes nach [`VertexElementMaterial`](../../vertexelementmaterial/) aufteilen. Jeder Sub-Mesh verwendet nur ein Material. Mesh-Aufteilung an einem Knoten durchführen.

```csharp
public static void SplitMesh(Node node, SplitMeshPolicy policy, bool createChildNodes = false, 
    bool removeOldMesh = true)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Knoten | Knoten |  |
| Richtlinie | SplitMeshPolicy |  |
| createChildNodes | Boolean | Erstelle Kindknoten für jedes Sub-Mesh. |
| removeOldMesh | Boolean | Entferne das alte Mesh nach dem Aufteilen; wenn dieser Parameter false ist, existieren das alte und das neue Mesh gleichzeitig. |

## Beispiele

Der folgende Code zeigt, wie man eine Box mit Materialindizes in Sub-Meshes aufteilt.

```csharp
// Erstelle ein Mesh einer Box (eine Box besteht aus 6 Ebenen).
Mesh box = (new Box()).ToMesh();
// Erstelle ein Material-Element auf diesem Mesh.
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// Und gib für jede Ebene einen anderen Materialindex an.
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// Jetzt teilen wir es in 6 Sub-Meshes auf, wir haben für jede Ebene 6 verschiedene Materialien angegeben, jede Ebene wird zu einem Sub-Mesh.
// Wir haben die CloneData-Richtlinie verwendet, jede Ebene hat dieselben Kontrollpunktinformationen oder kontrollpunktbasierten Vertex-Element-Informationen.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// Jetzt teilen wir es in 2 Sub-Meshes auf, das erste Mesh enthält die Ebenen 0/1/2 und das zweite Mesh enthält die Ebenen 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// Wir haben die CompactData-Richtlinie verwendet, jede Ebene hat ihre eigenen Kontrollpunktinformationen oder kontrollpunktbasierten Vertex-Element-Informationen.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### Siehe auch

* class [Node](../../../aspose.threed/node/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## SplitMesh(Scene, SplitMeshPolicy, bool) {#splitmesh_2}

Mesh in Sub-Meshes nach [`VertexElementMaterial`](../../vertexelementmaterial/) aufteilen. Jeder Sub-Mesh verwendet nur ein Material. Mesh-Aufteilung an allen Knoten der Szene durchführen.

```csharp
public static void SplitMesh(Scene scene, SplitMeshPolicy policy, bool removeOldMesh = true)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scene | Scene |  |
| Richtlinie | SplitMeshPolicy |  |
| removeOldMesh | Boolean |  |

## Beispiele

Der folgende Code zeigt, wie man eine Box mit Materialindizes in Sub-Meshes aufteilt.

```csharp
// Erstelle ein Mesh einer Box (eine Box besteht aus 6 Ebenen).
Mesh box = (new Box()).ToMesh();
// Erstelle ein Material-Element auf diesem Mesh.
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// Und gib für jede Ebene einen anderen Materialindex an.
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// Jetzt teilen wir es in 6 Sub-Meshes auf, wir haben für jede Ebene 6 verschiedene Materialien angegeben, jede Ebene wird zu einem Sub-Mesh.
// Wir haben die CloneData-Richtlinie verwendet, jede Ebene hat dieselben Kontrollpunktinformationen oder kontrollpunktbasierten Vertex-Element-Informationen.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// Jetzt teilen wir es in 2 Sub-Meshes auf, das erste Mesh enthält die Ebenen 0/1/2 und das zweite Mesh enthält die Ebenen 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// Wir haben die CompactData-Richtlinie verwendet, jede Ebene hat ihre eigenen Kontrollpunktinformationen oder kontrollpunktbasierten Vertex-Element-Informationen.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### Siehe auch

* class [Scene](../../../aspose.threed/scene/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## SplitMesh(Mesh, SplitMeshPolicy) {#splitmesh}

Mesh in Sub-Meshes nach [`VertexElementMaterial`](../../vertexelementmaterial/) aufteilen. Jeder Sub-Mesh verwendet nur ein Material. Das ursprüngliche Mesh wird nicht verändert.

```csharp
public static Mesh[] SplitMesh(Mesh mesh, SplitMeshPolicy policy)
```

### Rückgabewert

Neue gesplittete Meshes

## Beispiele

Der folgende Code zeigt, wie man eine Box mit Materialindizes in Sub-Meshes aufteilt.

```csharp
// Erstelle ein Mesh einer Box (eine Box besteht aus 6 Ebenen).
Mesh box = (new Box()).ToMesh();
// Erstelle ein Material-Element auf diesem Mesh.
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// Und gib für jede Ebene einen anderen Materialindex an.
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// Jetzt teilen wir es in 6 Sub-Meshes auf, wir haben für jede Ebene 6 verschiedene Materialien angegeben, jede Ebene wird zu einem Sub-Mesh.
// Wir haben die CloneData-Richtlinie verwendet, jede Ebene hat dieselben Kontrollpunktinformationen oder kontrollpunktbasierten Vertex-Element-Informationen.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// Jetzt teilen wir es in 2 Sub-Meshes auf, das erste Mesh enthält die Ebenen 0/1/2 und das zweite Mesh enthält die Ebenen 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// Wir haben die CompactData-Richtlinie verwendet, jede Ebene hat ihre eigenen Kontrollpunktinformationen oder kontrollpunktbasierten Vertex-Element-Informationen.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### Siehe auch

* class [Mesh](../../mesh/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


