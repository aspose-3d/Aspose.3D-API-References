---
title: "TransformBuilder.RotateDegree"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "TransformBuilder méthode. Enchaîner une transformation de rotation en degré"
type: docs
weight: 100
url: /fr/net/aspose.threed.utilities/transformbuilder/rotatedegree/
---
## RotateDegree(double, Vector3) {#rotatedegree}

Chaînez une transformation de rotation en degrés

```csharp
public TransformBuilder RotateDegree(double angle, Vector3 axis)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| angle | Double | L'angle à faire pivoter en degré |
| axis | Vector3 | L'axe de rotation |

## Exemples

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateDegree(90, Vector3.YAxis);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Voir aussi

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateDegree(Vector3, RotationOrder) {#rotatedegree_1}

Ajouter une rotation avec l'ordre spécifié

```csharp
public void RotateDegree(Vector3 rot, RotationOrder order)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rot | Vector3 | Rotation en degrés |
| ordre | RotationOrder |  |

### Voir aussi

* struct [Vector3](../../vector3/)
* enum [RotationOrder](../../rotationorder/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


