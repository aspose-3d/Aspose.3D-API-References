---
title: "Transform.SetGeometricRotation"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Transform. Définit la rotation d'Euler géométrique mesurée en degrés. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée comme transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge."
type: docs
weight: 160
url: /fr/net/aspose.threed/transform/setgeometricrotation/
---
## Transform.SetGeometricRotation method

Définit la rotation géométrique d'Euler (mesurée en degrés). La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge.

```csharp
public Transform SetGeometricRotation(double rx, double ry, double rz)
```

## Exemples

```csharp
Node node = new Node();
node.Transform.SetGeometricRotation(90, 0, 0);
```

### Voir aussi

* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)


