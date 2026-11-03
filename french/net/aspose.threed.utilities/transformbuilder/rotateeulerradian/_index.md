---
title: "TransformBuilder.RotateEulerRadian"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode TransformBuilder. Enchaîner une rotation par angles d'Euler en radians"
type: docs
weight: 120
url: /fr/net/aspose.threed.utilities/transformbuilder/rotateeulerradian/
---
## RotateEulerRadian(double, double, double) {#rotateeulerradian_1}

Enchaîner une rotation par angles d'Euler en radians

```csharp
public TransformBuilder RotateEulerRadian(double x, double y, double z)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| x | Double |  |
| y | Double |  |
| z | Double |  |

## Exemples

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerRadian(0, Math.PI, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Voir aussi

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateEulerRadian(Vector3) {#rotateeulerradian}

Enchaîner une rotation par angles d'Euler en radians

```csharp
public TransformBuilder RotateEulerRadian(Vector3 r)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| r | Vector3 |  |

## Exemples

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerRadian(new Vector3(0, Math.PI, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Voir aussi

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


