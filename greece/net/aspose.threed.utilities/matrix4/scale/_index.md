---
title: "Matrix4.Scale"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Matrix4. Δημιουργεί έναν πίνακα που κλιμακώνει κατά τον xaxis, τον yaxis και τον zaxis"
type: docs
weight: 50
url: /el/net/aspose.threed.utilities/matrix4/scale/
---
## Scale(Vector3) {#scale}

Δημιουργεί έναν πίνακα που κλιμακώνει κατά τον άξονα x, τον άξονα y και τον άξονα z.

```csharp
public static Matrix4 Scale(Vector3 s)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | Vector3 | Οι εργοστάσια κλιμάκωσης εφαρμόζονται στον x-axis, τον y-axis και τον z-axis |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν πίνακα για λειτουργία κλιμάκωσης.

```csharp
var t = Matrix4.Scale(new Vector3(10, 10, 10));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Δείτε επίσης

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Scale(double) {#scale_1}

Δημιουργεί έναν πίνακα που κλιμακώνει κατά τον άξονα x, τον άξονα y και τον άξονα z.

```csharp
public static Matrix4 Scale(double s)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | Διπλό | Τα εργοστάσια κλιμάκωσης εφαρμόζονται σε όλους τους άξονες |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν πίνακα για λειτουργία κλιμάκωσης.

```csharp
var t = Matrix4.Scale(10);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Δείτε επίσης

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Scale(double, double, double) {#scale_2}

Δημιουργεί έναν πίνακα που κλιμακώνει κατά τον άξονα x, τον άξονα y και τον άξονα z.

```csharp
public static Matrix4 Scale(double sx, double sy, double sz)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sx | Διπλό | Η κλιμάκωση των εργοστασίων εφαρμόζεται στον άξονα x |
| sy | Διπλό | Η κλιμάκωση των εργοστασίων εφαρμόζεται στον άξονα y |
| sz | Διπλό | Η κλιμάκωση των εργοστασίων εφαρμόζεται στον άξονα z |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν πίνακα για λειτουργία κλιμάκωσης.

```csharp
var t = Matrix4.Scale(10, 20, 10);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Δείτε επίσης

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


