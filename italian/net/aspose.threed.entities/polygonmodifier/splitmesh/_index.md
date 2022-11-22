---
title: SplitMesh
second_title: Riferimento API Aspose.3D per .NET
description: Dividi la mesh in sottomesh perVertexElementMaterialaspose.threed.entities/vertexelementmaterial . Ogni submesh utilizzerà un solo materiale. Esegui la divisione della mesh su un nodo
type: docs
weight: 60
url: /it/net/aspose.threed.entities/polygonmodifier/splitmesh/
---
## SplitMesh(Node, SplitMeshPolicy, bool, bool) {#splitmesh_1}

Dividi la mesh in sottomesh per[`VertexElementMaterial`](../../vertexelementmaterial) . Ogni sub-mesh utilizzerà un solo materiale. Esegui la divisione della mesh su un nodo

```csharp
public static void SplitMesh(Node node, SplitMeshPolicy policy, bool createChildNodes = false, 
    bool removeOldMesh = true)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | Node |  |
| policy | SplitMeshPolicy |  |
| createChildNodes | Boolean | Crea nodi figlio per ogni sotto-mesh. |
| removeOldMesh | Boolean | Rimuovi la vecchia mesh dopo la divisione, se questo parametro è falso, la vecchia e la nuova mesh coesisteranno. |

### Guarda anche

* class [Node](../../../aspose.threed/node)
* enum [SplitMeshPolicy](../../splitmeshpolicy)
* class [PolygonModifier](../../polygonmodifier)
* spazio dei nomi [Aspose.ThreeD.Entities](../../polygonmodifier)
* assemblea [Aspose.3D](../../../)

---

## SplitMesh(Scene, SplitMeshPolicy, bool) {#splitmesh_2}

Dividi la mesh in sottomesh per[`VertexElementMaterial`](../../vertexelementmaterial) . Ogni sub-mesh utilizzerà un solo materiale. Esegui la divisione della mesh su tutti i nodi della scena.

```csharp
public static void SplitMesh(Scene scene, SplitMeshPolicy policy, bool removeOldMesh = true)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scene | Scene |  |
| policy | SplitMeshPolicy |  |
| removeOldMesh | Boolean |  |

### Guarda anche

* class [Scene](../../../aspose.threed/scene)
* enum [SplitMeshPolicy](../../splitmeshpolicy)
* class [PolygonModifier](../../polygonmodifier)
* spazio dei nomi [Aspose.ThreeD.Entities](../../polygonmodifier)
* assemblea [Aspose.3D](../../../)

---

## SplitMesh(Mesh, SplitMeshPolicy) {#splitmesh}

Dividi la mesh in sottomesh per[`VertexElementMaterial`](../../vertexelementmaterial) . Ogni sottorete utilizzerà un solo materiale. La mesh originale non verrà modificata.

```csharp
public static Mesh[] SplitMesh(Mesh mesh, SplitMeshPolicy policy)
```

### Guarda anche

* class [Mesh](../../mesh)
* enum [SplitMeshPolicy](../../splitmeshpolicy)
* class [PolygonModifier](../../polygonmodifier)
* spazio dei nomi [Aspose.ThreeD.Entities](../../polygonmodifier)
* assemblea [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->