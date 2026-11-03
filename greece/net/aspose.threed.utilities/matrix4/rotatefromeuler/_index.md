---
title: "Matrix4.RotateFromEuler"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Matrix4. Δημιουργήστε έναν πίνακα περιστροφής από γωνία Euler"
type: docs
weight: 40
url: /el/net/aspose.threed.utilities/matrix4/rotatefromeuler/
---
## RotateFromEuler(Vector3) {#rotatefromeuler}

Δημιουργεί έναν πίνακα περιστροφής από γωνία Euler

```csharp
public static Matrix4 RotateFromEuler(Vector3 eul)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| eul | Vector3 | Περιστροφή σε ακτίνια |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν πίνακα για λειτουργία περιστροφής.

```csharp
var t = Matrix4.RotateFromEuler(new Vector3(0, Math.PI, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Δείτε επίσης

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## RotateFromEuler(double, double, double) {#rotatefromeuler_1}

Δημιουργεί έναν πίνακα περιστροφής από γωνία Euler

```csharp
public static Matrix4 RotateFromEuler(double rx, double ry, double rz)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rx | Διπλό | Περιστροφή στον άξονα x σε ακτίνια |
| ry | Διπλό | Περιστροφή στον άξονα y σε ακτίνια |
| rz | Διπλό | Περιστροφή στον άξονα z σε ακτίνια |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν πίνακα για λειτουργία περιστροφής.

```csharp
var t = Matrix4.RotateFromEuler(0, Math.PI, 0);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Δείτε επίσης

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


