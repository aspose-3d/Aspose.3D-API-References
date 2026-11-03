---
title: "TriMesh.CopyFrom"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode TriMesh. Copier le TriMesh depuis l'entrée avec une nouvelle disposition de sommet"
type: docs
weight: 20
url: /fr/net/aspose.threed.entities/trimesh/copyfrom/
---
## TriMesh.CopyFrom method

Copier le [`TriMesh`](../) depuis l'entrée avec une nouvelle disposition de sommet

```csharp
public static TriMesh CopyFrom(TriMesh input, VertexDeclaration vd)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | TriMesh | Le TriMesh d'entrée pour la copie |
| vd | VertexDeclaration | La nouvelle déclaration de sommet du TriMesh de sortie |

### Valeur de retour

Une nouvelle instance TriMesh avec une nouvelle déclaration de sommet.

## Exemples

```csharp
//Définir une déclaration de sommet comme {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//convertir un maillage en TriMesh, la disposition est automatiquement déduite du maillage d'entrée
var oldTriMesh = TriMesh.FromMesh((new Sphere()).ToMesh());
//maintenant créez un nouveau TriMesh à partir d'un ancien TriMesh, en utilisant la disposition mémoire explicite définie par vd
var newTriMesh = TriMesh.CopyFrom(oldTriMesh, vd);
```

### Voir aussi

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


