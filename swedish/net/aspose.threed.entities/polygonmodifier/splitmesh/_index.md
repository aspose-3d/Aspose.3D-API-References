---
title: SplitMesh
second_title: Aspose.3D för .NET API-referens
description: Dela mesh i submaskor genomVertexElementMaterialaspose.threed.entities/vertexelementmaterial . Varje submesh kommer att använda endast ett material. Utför meshdelning på en node
type: docs
weight: 60
url: /sv/net/aspose.threed.entities/polygonmodifier/splitmesh/
---
## SplitMesh(Node, SplitMeshPolicy, bool, bool) {#splitmesh_1}

Dela mesh i sub-maskor genom[`VertexElementMaterial`](../../vertexelementmaterial) . Varje sub-mesh kommer att använda endast ett material. Utför mesh-delning på en node

```csharp
public static void SplitMesh(Node node, SplitMeshPolicy policy, bool createChildNodes = false, 
    bool removeOldMesh = true)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | Node |  |
| policy | SplitMeshPolicy |  |
| createChildNodes | Boolean | Skapa underordnade noder för varje sub-mesh. |
| removeOldMesh | Boolean | Ta bort det gamla nätet efter uppdelningen, om denna parameter är falsk kommer de gamla och nya maskorna att samexistera. |

### Se även

* class [Node](../../../aspose.threed/node)
* enum [SplitMeshPolicy](../../splitmeshpolicy)
* class [PolygonModifier](../../polygonmodifier)
* namnutrymme [Aspose.ThreeD.Entities](../../polygonmodifier)
* hopsättning [Aspose.3D](../../../)

---

## SplitMesh(Scene, SplitMeshPolicy, bool) {#splitmesh_2}

Dela mesh i sub-maskor genom[`VertexElementMaterial`](../../vertexelementmaterial) . Varje sub-mesh kommer att använda endast ett material. Utför mesh-delning på alla noder i scenen.

```csharp
public static void SplitMesh(Scene scene, SplitMeshPolicy policy, bool removeOldMesh = true)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scene | Scene |  |
| policy | SplitMeshPolicy |  |
| removeOldMesh | Boolean |  |

### Se även

* class [Scene](../../../aspose.threed/scene)
* enum [SplitMeshPolicy](../../splitmeshpolicy)
* class [PolygonModifier](../../polygonmodifier)
* namnutrymme [Aspose.ThreeD.Entities](../../polygonmodifier)
* hopsättning [Aspose.3D](../../../)

---

## SplitMesh(Mesh, SplitMeshPolicy) {#splitmesh}

Dela mesh i sub-maskor genom[`VertexElementMaterial`](../../vertexelementmaterial) . Varje sub-mesh kommer att använda endast ett material. Det ursprungliga nätet kommer inte att ändras.

```csharp
public static Mesh[] SplitMesh(Mesh mesh, SplitMeshPolicy policy)
```

### Se även

* class [Mesh](../../mesh)
* enum [SplitMeshPolicy](../../splitmeshpolicy)
* class [PolygonModifier](../../polygonmodifier)
* namnutrymme [Aspose.ThreeD.Entities](../../polygonmodifier)
* hopsättning [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
