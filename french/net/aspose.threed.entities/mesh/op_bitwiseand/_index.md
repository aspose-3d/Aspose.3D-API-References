---
title: "Mesh.op_BitwiseAnd"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Mesh. Calcule l'intersection de deux maillages"
type: docs
weight: 130
url: /fr/net/aspose.threed.entities/mesh/op_bitwiseand/
---
## Mesh BitwiseAnd operator

Calcule l'intersection de deux maillages

```csharp
public static Mesh operator &(Mesh a, Mesh b)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| a | Maillage | Premier maillage |
| b | Maillage | Deuxième maillage |

### Valeur de retour

Maillage résultant

## Exemples

Le code suivant montre comment calculer la différence entre deux maillages :

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
Mesh merged = box1 & box2;
```

### Voir aussi

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


