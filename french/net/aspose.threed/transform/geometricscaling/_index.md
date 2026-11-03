---
title: "Transform.GeometricScaling"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété Transform. Obtient ou définit le redimensionnement géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée comme transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge."
type: docs
weight: 30
url: /fr/net/aspose.threed/transform/geometricscaling/
---
## Transform.GeometricScaling property

Obtient ou définit l'échelle géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge.

```csharp
public Vector3 GeometricScaling { get; set; }
```

## Exemples

```csharp
Node node = new Node();
node.Transform.GeometricScaling = new Vector3(2, 2, 2);
```

### Voir aussi

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)


