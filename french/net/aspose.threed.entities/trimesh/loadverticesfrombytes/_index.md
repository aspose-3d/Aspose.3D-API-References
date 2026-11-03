---
title: "TriMesh.LoadVerticesFromBytes"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode TriMesh. Charger les sommets à partir d'octets, la longueur des octets doit être un multiple entier de la taille du sommet"
type: docs
weight: 160
url: /fr/net/aspose.threed.entities/trimesh/loadverticesfrombytes/
---
## TriMesh.LoadVerticesFromBytes method

Charger les sommets à partir d'octets, la longueur des octets doit être un multiple entier de la taille d'un sommet.

```csharp
public void LoadVerticesFromBytes(byte[] verticesInBytes)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| verticesInBytes | Byte[] |  |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException |  |
| ArgumentException |  |

## Exemples

Le code suivant montre comment créer un TriMesh vide et charger manuellement les sommets à partir d'octets bruts.

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
//créer un TriMesh vide avec une déclaration de sommet spécifiée
var triMesh = new TriMesh("", vd);
//charger les sommets directement à partir d'octets
triMesh.LoadVerticesFromBytes(vertices);
triMesh.AddTriangle(0, 1, 2);
```

```csharp
int[] indices = new int[] { 0,  1,  2 };
byte[] vertices = new byte[]{
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
vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
//créer un TriMesh vide avec une déclaration de sommet spécifiée
var triMesh = new TriMesh("", vd);
//charger les sommets directement à partir d'octets
triMesh.loadVerticesFromBytes(vertices);
triMesh.addTriangle(0, 1, 2);
```

### Voir aussi

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


