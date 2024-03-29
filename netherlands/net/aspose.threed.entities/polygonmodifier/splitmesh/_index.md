---
title: SplitMesh
second_title: Aspose.3D voor .NET API-referentie
description: Split mesh in submeshes doorVertexElementMaterialaspose.threed.entities/vertexelementmaterial/ . Elke submesh gebruikt slechts één materiaal. Voer meshsplitsing uit op een knooppunt
type: docs
weight: 60
url: /nl/net/aspose.threed.entities/polygonmodifier/splitmesh/
---
## SplitMesh(Node, SplitMeshPolicy, bool, bool) {#splitmesh_1}

Split mesh in sub-meshes door[`VertexElementMaterial`](../../vertexelementmaterial/) . Elke sub-mesh gebruikt slechts één materiaal. Voer mesh-splitsing uit op een knooppunt

```csharp
public static void SplitMesh(Node node, SplitMeshPolicy policy, bool createChildNodes = false, 
    bool removeOldMesh = true)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | Node |  |
| policy | SplitMeshPolicy |  |
| createChildNodes | Boolean | Maak onderliggende knooppunten voor elke sub-mesh. |
| removeOldMesh | Boolean | Verwijder de oude mesh na splitsing, als deze parameter onwaar is, zullen de oude en nieuwe meshes naast elkaar bestaan. |

### Zie ook

* class [Node](../../../aspose.threed/node/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* naamruimte [Aspose.ThreeD.Entities](../../polygonmodifier/)
* montage [Aspose.3D](../../../)

---

## SplitMesh(Scene, SplitMeshPolicy, bool) {#splitmesh_2}

Split mesh in sub-meshes door[`VertexElementMaterial`](../../vertexelementmaterial/) . Elke sub-mesh gebruikt slechts één materiaal. Voer mesh-splitsing uit op alle knooppunten van de scène.

```csharp
public static void SplitMesh(Scene scene, SplitMeshPolicy policy, bool removeOldMesh = true)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scene | Scene |  |
| policy | SplitMeshPolicy |  |
| removeOldMesh | Boolean |  |

### Zie ook

* class [Scene](../../../aspose.threed/scene/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* naamruimte [Aspose.ThreeD.Entities](../../polygonmodifier/)
* montage [Aspose.3D](../../../)

---

## SplitMesh(Mesh, SplitMeshPolicy) {#splitmesh}

Split mesh in sub-meshes door[`VertexElementMaterial`](../../vertexelementmaterial/) . Elke sub-mesh gebruikt slechts één materiaal. De originele mesh wordt niet gewijzigd.

```csharp
public static Mesh[] SplitMesh(Mesh mesh, SplitMeshPolicy policy)
```

### Zie ook

* class [Mesh](../../mesh/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* naamruimte [Aspose.ThreeD.Entities](../../polygonmodifier/)
* montage [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
