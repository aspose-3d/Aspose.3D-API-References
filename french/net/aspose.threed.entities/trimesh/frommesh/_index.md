---
title: "TriMesh.FromMesh"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode TriMesh. Créer un TriMesh à partir d'un objet maillage donné avec la disposition de vertex donnée"
type: docs
weight: 30
url: /fr/net/aspose.threed.entities/trimesh/frommesh/
---
## FromMesh(VertexDeclaration, Mesh) {#frommesh_1}

Créer un TriMesh à partir d'un objet maillage donné avec la disposition des sommets fournie.

```csharp
public static TriMesh FromMesh(VertexDeclaration declaration, Mesh mesh)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| déclaration | VertexDeclaration | Définition du type de Vertex, ou disposition mémoire |
| maillage | Maillage | Maillage source |

### Valeur de retour

Instance de TriMesh convertie à partir du maillage d'entrée avec la disposition mémoire du vertex spécifié

## Exemples

Le code suivant montre comment créer un TriMesh avec une disposition mémoire personnalisée, et l'exporter vers un fichier.

```csharp
//Définir une déclaration de sommet comme {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//convertir un maillage en tri-mesh en utilisant la disposition mémoire spécifiée
var mesh = (new Sphere()).ToMesh();
var triMesh = TriMesh.FromMesh(vd, mesh);
//l'enregistrer dans un flux, 115 sommets * 32 octets par sommet
using (var stream = new FileStream("output.bin", FileMode.Create))
{
    triMesh.WriteVerticesTo(stream);
    //enregistrer les indices en ushort dans le flux, 504 indices * 2 octets par indice
    triMesh.Write16bIndicesTo(stream);
}
```

### Voir aussi

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [Mesh](../../mesh/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)

---

## FromMesh(Mesh, bool) {#frommesh}

Créer un TriMesh à partir d'un objet maillage donné, la déclaration des sommets étant basée sur la structure du maillage d'entrée.

```csharp
public static TriMesh FromMesh(Mesh mesh, bool useFloat = true)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| maillage | Maillage |  |
| useFloat | Boolean | Utiliser le type float au lieu du type double pour chaque composant d'élément de vertex. |

### Valeur de retour

Le [`TriMesh`](../) généré à partir du [`Mesh`](../../mesh/)

## Exemples

Le code suivant montre comment créer un TriMesh avec une disposition mémoire personnalisée, et l'exporter vers un fichier.

```csharp
//Définir une déclaration de sommet comme {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//convertir un maillage en tri-mesh en utilisant la disposition mémoire spécifiée
var mesh = (new Sphere()).ToMesh();
var triMesh = TriMesh.FromMesh(vd, mesh);
//l'enregistrer dans un flux, 115 sommets * 32 octets par sommet
using (var stream = new FileStream("output.bin", FileMode.Create))
{
    triMesh.WriteVerticesTo(stream);
    //enregistrer les indices en ushort dans le flux, 504 indices * 2 octets par indice
    triMesh.Write16bIndicesTo(stream);
}
```

### Voir aussi

* class [Mesh](../../mesh/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


