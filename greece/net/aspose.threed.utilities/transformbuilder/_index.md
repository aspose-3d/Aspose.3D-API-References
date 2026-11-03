---
title: "Κλάση TransformBuilder"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Utilities.TransformBuilder. Το TransformBuilder χρησιμοποιείται για τη δημιουργία πίνακα μετασχηματισμού μέσω μιας αλυσίδας μετασχηματισμών"
type: docs
weight: 2860
url: /el/net/aspose.threed.utilities/transformbuilder/
---
## TransformBuilder class

Το `TransformBuilder` χρησιμοποιείται για τη δημιουργία πίνακα μετασχηματισμού μέσω μιας αλυσίδας μετασχηματισμών.

```csharp
public class TransformBuilder
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [TransformBuilder](transformbuilder/#constructor)(ComposeOrder) | Δομήστε ένα `TransformBuilder` με αρχικό πίνακα ταυτότητας μετασχηματισμού και καθορισμένη σειρά σύνθεσης |
| [TransformBuilder](transformbuilder/#constructor_1)(Matrix4, ComposeOrder) | Δομήστε ένα `TransformBuilder` με αρχικό πίνακα μετασχηματισμού και καθορισμένη σειρά σύνθεσης |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ComposeOrder](../../aspose.threed.utilities/transformbuilder/composeorder/) { get; set; } | Λαμβάνει ή ορίζει τη σειρά σύνθεσης της αλυσίδας. |
| [Matrix](../../aspose.threed.utilities/transformbuilder/matrix/) { get; set; } | Λαμβάνει ή ορίζει την τρέχουσα τιμή του πίνακα |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Append](../../aspose.threed.utilities/transformbuilder/append/)(Matrix4) | Προσθέστε τον νέο πίνακα μετασχηματισμού στην αλυσίδα μετασχηματισμού. |
| [Compose](../../aspose.threed.utilities/transformbuilder/compose/)(Matrix4) | Προσθέστε ή τοποθετήστε στην αρχή το όρισμα στον εσωτερικό πίνακα. |
| [Prepend](../../aspose.threed.utilities/transformbuilder/prepend/)(Matrix4) | Τοποθετήστε στην αρχή τον νέο πίνακα μετασχηματισμού στην αλυσίδα μετασχηματισμού. |
| [Rearrange](../../aspose.threed.utilities/transformbuilder/rearrange/)(Axis, Axis, Axis) | Αναδιατάξτε τη διάταξη του άξονα. |
| [Reset](../../aspose.threed.utilities/transformbuilder/reset/)() | Επαναφέρετε τον μετασχηματισμό σε πίνακα ταυτότητας |
| [Rotate](../../aspose.threed.utilities/transformbuilder/rotate/)(Quaternion) | Αλυσίδα περιστροφής με quaternion |
| [RotateDegree](../../aspose.threed.utilities/transformbuilder/rotatedegree/#rotatedegree)(double, Vector3) | Αλυσίδα περιστροφής σε μοίρες |
| [RotateDegree](../../aspose.threed.utilities/transformbuilder/rotatedegree/#rotatedegree_1)(Vector3, RotationOrder) | Προσθήκη περιστροφής με καθορισμένη σειρά |
| [RotateEulerDegree](../../aspose.threed.utilities/transformbuilder/rotateeulerdegree/)(double, double, double) | Αλυσίδα περιστροφής με γωνίες Euler σε μοίρες |
| [RotateEulerRadian](../../aspose.threed.utilities/transformbuilder/rotateeulerradian/#rotateeulerradian)(Vector3) | Αλυσίδα περιστροφής με γωνίες Euler σε ακτίνια |
| [RotateEulerRadian](../../aspose.threed.utilities/transformbuilder/rotateeulerradian/#rotateeulerradian_1)(double, double, double) | Αλυσίδα περιστροφής με γωνίες Euler σε ακτίνια |
| [RotateRadian](../../aspose.threed.utilities/transformbuilder/rotateradian/#rotateradian)(double, Vector3) | Αλυσίδα μετασχηματισμού περιστροφής σε ακτίνια |
| [RotateRadian](../../aspose.threed.utilities/transformbuilder/rotateradian/#rotateradian_1)(Vector3, RotationOrder) | Προσθήκη περιστροφής με καθορισμένη σειρά |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale_1)(double) | Αλυσίδα πίνακα μετασχηματισμού κλιμάκωσης με ένα στοιχείο κλιμακωμένο κατά s |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale)(Vector3) | Αλυσίδα μετασχηματισμού κλίμακας |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale_2)(double, double, double) | Αλυσίδα πίνακα μετασχηματισμού κλιμάκωσης |
| [Translate](../../aspose.threed.utilities/transformbuilder/translate/#translate)(Vector3) | Αλυσίδα μετασχηματισμού μετάφρασης |
| [Translate](../../aspose.threed.utilities/transformbuilder/translate/#translate_1)(double, double, double) | Αλυσίδα μετασχηματισμού μετάφρασης |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν πίνακα με ένα σύνολο λειτουργιών

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(10, 20, 0);
tb.Scale(10, 10, 10);
tb.RotateEulerDegree(90, 0, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Δείτε επίσης

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


