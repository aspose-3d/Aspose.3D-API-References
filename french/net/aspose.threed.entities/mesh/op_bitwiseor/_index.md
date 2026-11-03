---
title: "Mesh.op_BitwiseOr"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Mesh. Calcule l'union de deux maillages"
type: docs
weight: 140
url: /fr/net/aspose.threed.entities/mesh/op_bitwiseor/
---
## Mesh BitwiseOr operator

Calcule l'union de deux maillages

```csharp
public static Mesh operator |(Mesh a, Mesh b)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| a | Maillage | Premier maillage |
| b | Maillage | Deuxième maillage |

### Valeur de retour

Maillage résultant

## Exemples

Le code suivant montre comment unir deux maillages en un seul maillage :

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
var merged = box1 | box2;
```

### Voir aussi

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


