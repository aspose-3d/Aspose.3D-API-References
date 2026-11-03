---
title: "Transform.GeometricTranslation"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété Transform. Obtient ou définit la translation géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée comme transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge."
type: docs
weight: 40
url: /fr/net/aspose.threed/transform/geometrictranslation/
---
## Transform.GeometricTranslation property

Obtient ou définit la translation géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge.

```csharp
public Vector3 GeometricTranslation { get; set; }
```

## Exemples

```csharp
Node node = new Node();
node.Transform.GeometricTranslation = new Vector3(10, 0, 0);
```

### Voir aussi

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)


