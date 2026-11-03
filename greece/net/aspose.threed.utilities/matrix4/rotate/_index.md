---
title: "Matrix4.Rotate"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Matrix4 μέθοδος. Δημιουργεί ένα matrix περιστροφής με γωνία περιστροφής και άξονα"
type: docs
weight: 30
url: /el/net/aspose.threed.utilities/matrix4/rotate/
---
## Rotate(double, Vector3) {#rotate_1}

Δημιουργεί έναν πίνακα περιστροφής με γωνία περιστροφής και άξονα

```csharp
public static Matrix4 Rotate(double angle, Vector3 axis)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | Διπλό | Γωνία περιστροφής σε ακτίνια |
| άξονας | Vector3 | Άξονας περιστροφής |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν πίνακα για λειτουργία περιστροφής.

```csharp
var t = Matrix4.Rotate(Math.PI, new Vector3(0, 1, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Δείτε επίσης

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Rotate(Quaternion) {#rotate}

Δημιουργεί έναν πίνακα περιστροφής από ένα quaternion

```csharp
public static Matrix4 Rotate(Quaternion q)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| q | Τεταρτοπλέγμα | Τεταρτοπλέγμα περιστροφής |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν πίνακα για λειτουργία περιστροφής.

```csharp
var t = Matrix4.Rotate(Quaternion.FromAngleAxis(Math.PI, Vector3.YAxis));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Δείτε επίσης

* struct [Quaternion](../../quaternion/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


