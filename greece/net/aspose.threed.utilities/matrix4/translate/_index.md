---
title: "Matrix4.Translate"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Matrix4 μέθοδος. Δημιουργεί έναν πίνακα που μεταφράζει κατά τον άξονα x, τον άξονα y και τον άξονα z"
type: docs
weight: 60
url: /el/net/aspose.threed.utilities/matrix4/translate/
---
## Translate(Vector3) {#translate}

Δημιουργεί έναν πίνακα που μεταφράζει κατά τον άξονα x, τον άξονα y και τον άξονα z

```csharp
public static Matrix4 Translate(Vector3 t)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| t | Vector3 | Μετατόπιση μετάφρασης |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν πίνακα για λειτουργία μετάφρασης.

```csharp
var t = Matrix4.Translate(new Vector3(10, 0, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Δείτε επίσης

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Translate(double, double, double) {#translate_1}

Δημιουργεί έναν πίνακα που μεταφράζει κατά τον άξονα x, τον άξονα y και τον άξονα z

```csharp
public static Matrix4 Translate(double tx, double ty, double tz)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tx | Διπλό | Μετατόπιση συντεταγμένης X |
| ty | Διπλό | Μετατόπιση συντεταγμένης Y |
| tz | Διπλό | Μετατόπιση συντεταγμένης Z |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν πίνακα για λειτουργία μετάφρασης.

```csharp
var t = Matrix4.Translate(10, 0, 0);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Δείτε επίσης

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


