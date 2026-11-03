---
title: "Δομή Quaternion"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Δομή Aspose.ThreeD.Utilities.Quaternion. Το Quaternion χρησιμοποιείται συνήθως για την εκτέλεση περιστροφής στην υπολογιστική γραφική"
type: docs
weight: 2810
url: /el/net/aspose.threed.utilities/quaternion/
---
## Quaternion structure

Το Quaternion συνήθως χρησιμοποιείται για την εκτέλεση περιστροφής στην υπολογιστική γραφική.

```csharp
public struct Quaternion
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Quaternion](quaternion/)(double, double, double, double) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Quaternion`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Length](../../aspose.threed.utilities/quaternion/length/) { get; } | Λαμβάνει το μήκος του quaternion |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [FromAngleAxis](../../aspose.threed.utilities/quaternion/fromangleaxis/)(double, Vector3) | Δημιουργεί ένα quaternion γύρω από τον δοσμένο άξονα και περιστρέφει δεξιόστροφα |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle/#fromeulerangle)(Vector3) | Δημιουργεί quaternion από τη δοσμένη γωνία Euler |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle/#fromeulerangle_1)(double, double, double) | Δημιουργεί quaternion από τη δοσμένη γωνία Euler |
| static [FromRotation](../../aspose.threed.utilities/quaternion/fromrotation/)(Vector3, Vector3) | Δημιουργεί ένα quaternion που περιστρέφει από την αρχική προς την κατεύθυνση προορισμού |
| static [Interpolate](../../aspose.threed.utilities/quaternion/interpolate/)(float, Quaternion, Quaternion) | Γεμίζει αυτό το quaternion με την παρεμβαλλόμενη τιμή μεταξύ των δοσμένων ορισμάτων quaternion για μια τιμή t μεταξύ του από και του προς. |
| static [Slerp](../../aspose.threed.utilities/quaternion/slerp/)(double, Quaternion, Quaternion) | Εκτελεί σφαιρική γραμμική παρεμβολή μεταξύ δύο τιμών |
| [Concat](../../aspose.threed.utilities/quaternion/concat/)(Quaternion) | Συνενώνει δύο quaternions |
| [Conjugate](../../aspose.threed.utilities/quaternion/conjugate/)() | Επιστρέφει ένα συζυγές quaternion του τρέχοντος quaternion |
| [Dot](../../aspose.threed.utilities/quaternion/dot/)(Quaternion) | Προϊόν σημείων |
| override [Equals](../../aspose.threed.utilities/quaternion/equals/)(object) | Ελέγχει αν δύο quaternions είναι ίσα |
| [EulerAngles](../../aspose.threed.utilities/quaternion/eulerangles/)() | Μετατρέπει το quaternion σε περιστροφή που αναπαρίσταται από γωνίες Euler. Όλα τα συστατικά είναι σε ακτίνια |
| override [GetHashCode](../../aspose.threed.utilities/quaternion/gethashcode/)() | Λαμβάνει τον κωδικό κατακερματισμού του Quaternion |
| [Inverse](../../aspose.threed.utilities/quaternion/inverse/)() | Επιστρέφει ένα αντίστροφο quaternion του τρέχοντος quaternion |
| [Normalize](../../aspose.threed.utilities/quaternion/normalize/)() | Κανονικοποιεί το quaternion |
| [ToAngleAxis](../../aspose.threed.utilities/quaternion/toangleaxis/)(out double, out Vector3) |  |
| [ToMatrix](../../aspose.threed.utilities/quaternion/tomatrix/#tomatrix)() | Μετατρέπει τη περιστροφή που παρουσιάζεται από το quaternion σε πίνακα μετασχηματισμού. |
| [ToMatrix](../../aspose.threed.utilities/quaternion/tomatrix/#tomatrix_1)(Vector3) | Μετατρέπει τη περιστροφή που παρουσιάζεται από το quaternion σε πίνακα μετασχηματισμού. |
| override [ToString](../../aspose.threed.utilities/quaternion/tostring/)() | Λαμβάνει την αναπαράσταση του quaternion ως συμβολοσειρά |
| [operator +](../../aspose.threed.utilities/quaternion/op_addition/) | Υπερφόρτωση τελεστή για + |
| [operator /](../../aspose.threed.utilities/quaternion/op_division/) | Υπερφόρτωση τελεστή για / |
| [operator ==](../../aspose.threed.utilities/quaternion/op_equality/) | Τελεστής ισότητας για quaternion |
| [operator !=](../../aspose.threed.utilities/quaternion/op_inequality/) | Τελεστής ανισότητας για quaternion |
| [operator *](../../aspose.threed.utilities/quaternion/op_multiply/#op_multiply_1) | Υπερφόρτωση τελεστή για * (5 τελεστές) |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| static readonly [Identity](../../aspose.threed.utilities/quaternion/identity/) | Το quaternion ταυτότητας. |
| [W](../../aspose.threed.utilities/quaternion/w/) | Το συστατικό w. |
| [X](../../aspose.threed.utilities/quaternion/x/) | Το συστατικό x. |
| [Y](../../aspose.threed.utilities/quaternion/y/) | Το συστατικό y. |
| [Z](../../aspose.threed.utilities/quaternion/z/) | Το συστατικό z. |

### Δείτε επίσης

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


