---
title: "Mesh.Triangulate"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Mesh. Retourne le maillage triangulé"
type: docs
weight: 120
url: /fr/net/aspose.threed.entities/mesh/triangulate/
---
## Mesh.Triangulate method

Renvoie le maillage triangulé

```csharp
public Mesh Triangulate()
```

### Valeur de retour

Maillage actuel si le maillage actuel est déjà triangulé, sinon un nouveau maillage triangulé sera calculé et retourné

## Exemples

Le code suivant montre comment trianguler un maillage :

```csharp
//Le maillage plan ne possède qu'un seul polygone avec 4 points de contrôle
var mesh = (new Plane()).ToMesh();
//Après triangulation, le rectangle du nouveau maillage deviendra 2 triangles.
var triangulated = mesh.Triangulate();
```

### Voir aussi

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


