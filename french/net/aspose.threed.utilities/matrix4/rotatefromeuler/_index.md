---
title: "Matrix4.RotateFromEuler"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Matrix4. Créez une matrice de rotation à partir d'un angle d'Euler"
type: docs
weight: 40
url: /fr/net/aspose.threed.utilities/matrix4/rotatefromeuler/
---
## RotateFromEuler(Vector3) {#rotatefromeuler}

Crée une matrice de rotation à partir d'un angle d'Euler

```csharp
public static Matrix4 RotateFromEuler(Vector3 eul)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| eul | Vector3 | Rotation en radians |

## Exemples

Le code suivant montre comment créer une matrice pour l'opération de rotation.

```csharp
var t = Matrix4.RotateFromEuler(new Vector3(0, Math.PI, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Voir aussi

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## RotateFromEuler(double, double, double) {#rotatefromeuler_1}

Crée une matrice de rotation à partir d'un angle d'Euler

```csharp
public static Matrix4 RotateFromEuler(double rx, double ry, double rz)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rx | Double | Rotation autour de l'axe x en radians |
| ry | Double | Rotation autour de l'axe y en radians |
| rz | Double | Rotation autour de l'axe z en radians |

## Exemples

Le code suivant montre comment créer une matrice pour l'opération de rotation.

```csharp
var t = Matrix4.RotateFromEuler(0, Math.PI, 0);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Voir aussi

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


