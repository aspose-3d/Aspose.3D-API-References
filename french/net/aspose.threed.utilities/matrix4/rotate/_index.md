---
title: "Matrix4.Rotate"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Matrix4. Crée une matrice de rotation à partir de l'angle de rotation et de l'axe"
type: docs
weight: 30
url: /fr/net/aspose.threed.utilities/matrix4/rotate/
---
## Rotate(double, Vector3) {#rotate_1}

Crée une matrice de rotation à partir d'un angle de rotation et d'un axe

```csharp
public static Matrix4 Rotate(double angle, Vector3 axis)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| angle | Double | Angle de rotation en radian |
| axis | Vector3 | Axe de rotation |

## Exemples

Le code suivant montre comment créer une matrice pour l'opération de rotation.

```csharp
var t = Matrix4.Rotate(Math.PI, new Vector3(0, 1, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Voir aussi

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Rotate(Quaternion) {#rotate}

Crée une matrice de rotation à partir d'un quaternion

```csharp
public static Matrix4 Rotate(Quaternion q)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| q | Quaternion | Quaternion de rotation |

## Exemples

Le code suivant montre comment créer une matrice pour l'opération de rotation.

```csharp
var t = Matrix4.Rotate(Quaternion.FromAngleAxis(Math.PI, Vector3.YAxis));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Voir aussi

* struct [Quaternion](../../quaternion/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


