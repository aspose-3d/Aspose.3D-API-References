---
title: "Geometry.CreateElement"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Geometry. Crée un élément de sommet avec le type spécifié et l'ajoute à la géométrie"
type: docs
weight: 90
url: /fr/net/aspose.threed.entities/geometry/createelement/
---
## CreateElement(VertexElementType) {#createelement}

Crée un élément de sommet avec le type spécifié et l'ajoute à la géométrie.

```csharp
public VertexElement CreateElement(VertexElementType type)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| type | VertexElementType | Type d'élément de sommet |

### Valeur de retour

Élément créé.

## Remarques

Si le type est UV, un [`VertexElementUV`](../../vertexelementuv/) avec le type de mappage de texture à Diffuse sera créé.

### Voir aussi

* class [VertexElement](../../vertexelement/)
* enum [VertexElementType](../../vertexelementtype/)
* class [Geometry](../)
* namespace [Aspose.ThreeD.Entities](../../geometry/)
* assembly [Aspose.3D](../../../)

---

## CreateElement(VertexElementType, MappingMode, ReferenceMode) {#createelement_1}

Crée un élément de sommet avec le type spécifié et l'ajoute à la géométrie.

```csharp
public VertexElement CreateElement(VertexElementType type, MappingMode mappingMode, 
    ReferenceMode referenceMode)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| type | VertexElementType | Type d'élément de sommet |
| mappingMode | MappingMode | Mode de mappage par défaut |
| referenceMode | ReferenceMode | Mode de référence par défaut |

### Valeur de retour

Élément créé.

## Remarques

Si le type est UV, un [`VertexElementUV`](../../vertexelementuv/) avec le type de mappage de texture à Diffuse sera créé.

### Voir aussi

* class [VertexElement](../../vertexelement/)
* enum [VertexElementType](../../vertexelementtype/)
* enum [MappingMode](../../mappingmode/)
* enum [ReferenceMode](../../referencemode/)
* class [Geometry](../)
* namespace [Aspose.ThreeD.Entities](../../geometry/)
* assembly [Aspose.3D](../../../)


