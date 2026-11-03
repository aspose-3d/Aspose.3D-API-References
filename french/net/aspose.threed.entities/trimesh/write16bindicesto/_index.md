---
title: "TriMesh.Write16bIndicesTo"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode TriMesh. Écrire les données d'indices en entier 16 bits dans le flux"
type: docs
weight: 270
url: /fr/net/aspose.threed.entities/trimesh/write16bindicesto/
---
## TriMesh.Write16bIndicesTo method

Écrire les données d'indices en entier 16 bits dans le flux

```csharp
public void Write16bIndicesTo(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux |  |

## Exemples

```csharp
//convertir un maillage en TriMesh, la disposition est automatiquement déduite du maillage d'entrée
var triMesh = TriMesh.FromMesh(new Sphere().ToMesh());
//l'enregistrer dans un flux, 115 sommets * 32 octets par sommet
var stream = new MemoryStream();
triMesh.WriteVerticesTo(stream);
//enregistrer les indices en ushort dans le flux, 504 indices * 2 octets par indice
triMesh.Write16bIndicesTo(stream);
```

### Voir aussi

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


