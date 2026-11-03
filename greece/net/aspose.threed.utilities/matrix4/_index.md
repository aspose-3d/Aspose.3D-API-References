---
title: "Δομή Matrix4"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Δομή Aspose.ThreeD.Utilities.Matrix4. Υλοποίηση πίνακα 4x4"
type: docs
weight: 2790
url: /el/net/aspose.threed.utilities/matrix4/
---
## Matrix4 structure

Υλοποίηση πίνακα 4x4.

```csharp
public struct Matrix4
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Matrix4](matrix4/#constructor_3)(double[]) | Αρχικοποιεί ένα νέο παράδειγμα της δομής `Matrix4`. |
| [Matrix4](matrix4/#constructor)(FMatrix4) | Δημιουργεί το `Matrix4` από ένα παράδειγμα [`FMatrix4`](../fmatrix4/) |
| [Matrix4](matrix4/#constructor_1)(Vector4, Vector4, Vector4, Vector4) | Δημιουργεί πίνακα από 4 σειρές. |
| [Matrix4](matrix4/#constructor_2)(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double) | Αρχικοποιεί ένα νέο παράδειγμα της δομής `Matrix4`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [Identity](../../aspose.threed.utilities/matrix4/identity/) { get; } | Λαμβάνει τον μοναδιαίο πίνακα. |
| [Determinant](../../aspose.threed.utilities/matrix4/determinant/) { get; } | Λαμβάνει το ορίζουσα του πίνακα. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate/#rotate)(Quaternion) | Δημιουργεί έναν πίνακα περιστροφής από ένα quaternion |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate/#rotate_1)(double, Vector3) | Δημιουργεί έναν πίνακα περιστροφής με γωνία περιστροφής και άξονα |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler/#rotatefromeuler)(Vector3) | Δημιουργεί έναν πίνακα περιστροφής από γωνία Euler |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler/#rotatefromeuler_1)(double, double, double) | Δημιουργεί έναν πίνακα περιστροφής από γωνία Euler |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale_1)(double) | Δημιουργεί έναν πίνακα που κλιμακώνει κατά τον άξονα x, τον άξονα y και τον άξονα z. |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale)(Vector3) | Δημιουργεί έναν πίνακα που κλιμακώνει κατά τον άξονα x, τον άξονα y και τον άξονα z. |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale_2)(double, double, double) | Δημιουργεί έναν πίνακα που κλιμακώνει κατά τον άξονα x, τον άξονα y και τον άξονα z. |
| static [Translate](../../aspose.threed.utilities/matrix4/translate/#translate)(Vector3) | Δημιουργεί έναν πίνακα που μεταφράζει κατά τον άξονα x, τον άξονα y και τον άξονα z |
| static [Translate](../../aspose.threed.utilities/matrix4/translate/#translate_1)(double, double, double) | Δημιουργεί έναν πίνακα που μεταφράζει κατά τον άξονα x, τον άξονα y και τον άξονα z |
| [Concatenate](../../aspose.threed.utilities/matrix4/concatenate/)(Matrix4) | Συνενώνει τους δύο πίνακες |
| [Decompose](../../aspose.threed.utilities/matrix4/decompose/)(out Vector3, out Vector3, out Quaternion) |  |
| [Inverse](../../aspose.threed.utilities/matrix4/inverse/)() | Αντιστρέφει αυτό το παράδειγμα. |
| [Normalize](../../aspose.threed.utilities/matrix4/normalize/)() | Κανονικοποιεί αυτήν την παρουσία. |
| [SetTRS](../../aspose.threed.utilities/matrix4/settrs/)(Vector3, Vector3, Vector3) | Αρχικοποιεί τον πίνακα με μετάφραση/περιστροφή/κλίμακα |
| [ToArray](../../aspose.threed.utilities/matrix4/toarray/)() | Μετατρέπει τον πίνακα σε σειρά. |
| override [ToString](../../aspose.threed.utilities/matrix4/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει το τρέχον `Matrix4`. |
| [Transpose](../../aspose.threed.utilities/matrix4/transpose/)() | Κάνει transpose σε αυτό το στιγμιότυπο. |
| [operator *](../../aspose.threed.utilities/matrix4/op_multiply/#op_multiply) | Πολλαπλασιάζει τους δύο πίνακες (4 τελεστές) |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| [m00](../../aspose.threed.utilities/matrix4/m00/) | Το m00. |
| [m01](../../aspose.threed.utilities/matrix4/m01/) | Το m01. |
| [m02](../../aspose.threed.utilities/matrix4/m02/) | Το m02. |
| [m03](../../aspose.threed.utilities/matrix4/m03/) | Το m03. |
| [m10](../../aspose.threed.utilities/matrix4/m10/) | Το m10. |
| [m11](../../aspose.threed.utilities/matrix4/m11/) | Το m11. |
| [m12](../../aspose.threed.utilities/matrix4/m12/) | Το m12. |
| [m13](../../aspose.threed.utilities/matrix4/m13/) | Το m13. |
| [m20](../../aspose.threed.utilities/matrix4/m20/) | Το m20. |
| [m21](../../aspose.threed.utilities/matrix4/m21/) | Το m21. |
| [m22](../../aspose.threed.utilities/matrix4/m22/) | Το m22. |
| [m23](../../aspose.threed.utilities/matrix4/m23/) | Το m23. |
| [m30](../../aspose.threed.utilities/matrix4/m30/) | Το m30. |
| [m31](../../aspose.threed.utilities/matrix4/m31/) | Το m31. |
| [m32](../../aspose.threed.utilities/matrix4/m32/) | Το m32. |
| [m33](../../aspose.threed.utilities/matrix4/m33/) | Το m33. |

## Παραδείγματα

```csharp
Matrix4 mat = Matrix4.RotateFromEuler(90, 0, 0);
Matrix4 mat2 = Matrix4.Translate(0, 10, -50);
Matrix4 transform = mat2 * mat;
Vector4 pos = new Vector4(10, 9, 0, 1);
Vector4 transformed = transform * pos;

```

### Δείτε επίσης

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


