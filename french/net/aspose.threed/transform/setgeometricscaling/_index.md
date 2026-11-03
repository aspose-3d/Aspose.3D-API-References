---
title: "Transform.SetGeometricScaling"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Transform. Définit le redimensionnement géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée comme transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge."
type: docs
weight: 170
url: /fr/net/aspose.threed/transform/setgeometricscaling/
---
## Transform.SetGeometricScaling method

Définit l'échelle géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge.

```csharp
public Transform SetGeometricScaling(double sx, double sy, double sz)
```

## Exemples

```csharp
Node node = new Node();
node.Transform.SetGeometricScaling(2, 2, 2);
```

### Voir aussi

* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)


