---
title: "PolygonModifier.SplitMesh"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode PolygonModifier. Diviser le maillage en sous-maillages par VertexElementMaterial. Chaque sous-maillage utilisera un seul matériau. Effectuer la division du maillage sur un nœud."
type: docs
weight: 70
url: /fr/net/aspose.threed.entities/polygonmodifier/splitmesh/
---
## SplitMesh(Node, SplitMeshPolicy, bool, bool) {#splitmesh_1}

Diviser le maillage en sous-maillages par [`VertexElementMaterial`](../../vertexelementmaterial/). Chaque sous-maillage utilisera un seul matériau. Effectuer la division du maillage sur un nœud.

```csharp
public static void SplitMesh(Node node, SplitMeshPolicy policy, bool createChildNodes = false, 
    bool removeOldMesh = true)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nœud | Nœud |  |
| politique | SplitMeshPolicy |  |
| createChildNodes | Boolean | Créer des nœuds enfants pour chaque sous‑maillage. |
| removeOldMesh | Boolean | Supprimer le maillage ancien après la division, si ce paramètre est faux, les maillages ancien et nouveau coexisteront. |

## Exemples

Le code suivant montre comment diviser une boîte en sous‑maillages en utilisant les indices de matériau.

```csharp
// Crée un maillage d'une boîte (une boîte est composée de 6 plans)
Mesh box = (new Box()).ToMesh();
// Crée un élément de matériau sur ce maillage
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// Et spécifie un index de matériau différent pour chaque plan
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// Divisez‑le maintenant en 6 sous‑maillages, nous avons spécifié 6 matériaux différents sur chaque plan, chaque plan deviendra un sous‑maillage.
// Nous avons utilisé la politique CloneData, chaque plan aura les mêmes informations de points de contrôle ou les informations d’éléments de sommet basées sur les points de contrôle.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// Divisez‑le maintenant en 2 sous‑maillages, le premier maillage contiendra les plans 0/1/2, et le deuxième maillage contiendra les plans 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// Nous avons utilisé la politique CompactData, chaque plan aura ses propres informations de points de contrôle ou les informations d’éléments de sommet basées sur les points de contrôle.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### Voir aussi

* class [Node](../../../aspose.threed/node/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## SplitMesh(Scene, SplitMeshPolicy, bool) {#splitmesh_2}

Divisez le maillage en sous‑maillages par [`VertexElementMaterial`](../../vertexelementmaterial/). Chaque sous‑maillage utilisera un seul matériau. Effectuez la division du maillage sur tous les nœuds de la scène.

```csharp
public static void SplitMesh(Scene scene, SplitMeshPolicy policy, bool removeOldMesh = true)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| scène | Scène |  |
| politique | SplitMeshPolicy |  |
| removeOldMesh | Boolean |  |

## Exemples

Le code suivant montre comment diviser une boîte en sous‑maillages en utilisant les indices de matériau.

```csharp
// Crée un maillage d'une boîte (une boîte est composée de 6 plans)
Mesh box = (new Box()).ToMesh();
// Crée un élément de matériau sur ce maillage
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// Et spécifie un index de matériau différent pour chaque plan
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// Divisez‑le maintenant en 6 sous‑maillages, nous avons spécifié 6 matériaux différents sur chaque plan, chaque plan deviendra un sous‑maillage.
// Nous avons utilisé la politique CloneData, chaque plan aura les mêmes informations de points de contrôle ou les informations d’éléments de sommet basées sur les points de contrôle.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// Divisez‑le maintenant en 2 sous‑maillages, le premier maillage contiendra les plans 0/1/2, et le deuxième maillage contiendra les plans 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// Nous avons utilisé la politique CompactData, chaque plan aura ses propres informations de points de contrôle ou les informations d’éléments de sommet basées sur les points de contrôle.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### Voir aussi

* class [Scene](../../../aspose.threed/scene/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## SplitMesh(Mesh, SplitMeshPolicy) {#splitmesh}

Divisez le maillage en sous‑maillages par [`VertexElementMaterial`](../../vertexelementmaterial/). Chaque sous‑maillage utilisera un seul matériau. Le maillage original ne sera pas modifié.

```csharp
public static Mesh[] SplitMesh(Mesh mesh, SplitMeshPolicy policy)
```

### Valeur de retour

Nouveaux maillages découpés

## Exemples

Le code suivant montre comment diviser une boîte en sous‑maillages en utilisant les indices de matériau.

```csharp
// Crée un maillage d'une boîte (une boîte est composée de 6 plans)
Mesh box = (new Box()).ToMesh();
// Crée un élément de matériau sur ce maillage
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// Et spécifie un index de matériau différent pour chaque plan
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// Divisez‑le maintenant en 6 sous‑maillages, nous avons spécifié 6 matériaux différents sur chaque plan, chaque plan deviendra un sous‑maillage.
// Nous avons utilisé la politique CloneData, chaque plan aura les mêmes informations de points de contrôle ou les informations d’éléments de sommet basées sur les points de contrôle.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// Divisez‑le maintenant en 2 sous‑maillages, le premier maillage contiendra les plans 0/1/2, et le deuxième maillage contiendra les plans 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// Nous avons utilisé la politique CompactData, chaque plan aura ses propres informations de points de contrôle ou les informations d’éléments de sommet basées sur les points de contrôle.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### Voir aussi

* class [Mesh](../../mesh/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


