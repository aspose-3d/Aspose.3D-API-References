---
title: "TransformBuilder.RotateRadian"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "TransformBuilder méthode. Enchaîner une transformation de rotation en radian"
type: docs
weight: 130
url: /fr/net/aspose.threed.utilities/transformbuilder/rotateradian/
---
## RotateRadian(double, Vector3) {#rotateradian}

Enchaîner une transformation de rotation en radians

```csharp
public TransformBuilder RotateRadian(double angle, Vector3 axis)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| angle | Double | L'angle de rotation en radian |
| axis | Vector3 | L'axe de rotation |

## Exemples

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateRadian(Math.PI, Vector3.YAxis);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Voir aussi

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateRadian(Vector3, RotationOrder) {#rotateradian_1}

Ajouter une rotation avec l'ordre spécifié

```csharp
public void RotateRadian(Vector3 rot, RotationOrder order)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rot | Vector3 | Rotation en radians |
| ordre | RotationOrder |  |

## Exemples

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateRadian(new Vector3(0.3, 0.4, 0.1), RotationOrder.YZX);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Voir aussi

* struct [Vector3](../../vector3/)
* enum [RotationOrder](../../rotationorder/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


