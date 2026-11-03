---
title: "TriMesh.FromRawData"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode TriMesh. Crée un TriMesh à partir de données brutes"
type: docs
weight: 40
url: /fr/net/aspose.threed.entities/trimesh/fromrawdata/
---
## TriMesh.FromRawData method

Créer un TriMesh à partir de données brutes

```csharp
public static TriMesh FromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, 
    bool generateVertexMapping)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vd | VertexDeclaration | Déclaration du sommet, doit contenir au moins un champ. |
| vertices | Byte[] | Les données d'entrée du sommet, la longueur minimale des sommets doit être supérieure ou égale à la taille de la déclaration du sommet |
| indices | Int32[] | Les indices du triangle |
| generateVertexMapping | Boolean | Générez [`Vertex`](../../../aspose.threed.utilities/vertex/) pour chaque sommet, ce qui n'est pas nécessaire uniquement pour la sérialisation/désérialisation. |

### Valeur de retour

L'instance [`TriMesh`](../) qui encapsule le tableau d'octets d'entrée.

## Remarques

Le TriMesh retourné ne copiera pas le tableau d'octets d'entrée pour des raisons de performance, les modifications externes du tableau seront reflétées dans cette instance.

## Exemples

Le code suivant montre comment construire un TriMesh à partir d'octets bruts, ce qui est utile lors de la création de votre propre format 3D

```csharp
var indices = new int[] { 0,  1,  2 };
var vertices = new byte[]{
    0, 0, 0, 191,
    0, 0, 0, 0,
    0, 0, 0, 191,
    0, 0, 0, 191,
    0, 0, 0, 0,
    0, 0, 0, 63,
    0, 0, 0, 63,
    0, 0, 0, 0,
    0, 0, 0, 63
};
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
var triMesh = TriMesh.FromRawData(vd, vertices, indices, true);
```

### Voir aussi

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


