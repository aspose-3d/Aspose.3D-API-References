---
title: "TriMesh.WriteVerticesTo"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode TriMesh. Écrire les données des vertices dans le flux spécifié"
type: docs
weight: 290
url: /fr/net/aspose.threed.entities/trimesh/writeverticesto/
---
## TriMesh.WriteVerticesTo method

Écrire les données des sommets dans le flux spécifié

```csharp
public void WriteVerticesTo(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux dans lequel les données des vertices seront écrites |

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


