---
title: "Δομή Vector3"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Utilities.Vector3 struct. Ένα διάνυσμα με τρία συστατικά"
type: docs
weight: 2880
url: /el/net/aspose.threed.utilities/vector3/
---
## Vector3 structure

Ένα διάνυσμα με τρεις συνιστώσες.

```csharp
public struct Vector3 : IComparable<Vector3>
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Vector3](vector3/#constructor_2)(double) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής `Vector3`. |
| [Vector3](vector3/#constructor)(FVector3) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής `Vector3`. |
| [Vector3](vector3/#constructor_1)(Vector4) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής `Vector3`. |
| [Vector3](vector3/#constructor_3)(double, double, double) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής `Vector3`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [One](../../aspose.threed.utilities/vector3/one/) { get; } | Λαμβάνει διάνυσμα μονάδας (1, 1, 1) |
| static [UnitX](../../aspose.threed.utilities/vector3/unitx/) { get; } | Λαμβάνει διάνυσμα μονάδας (1, 0, 0) |
| static [UnitY](../../aspose.threed.utilities/vector3/unity/) { get; } | Λαμβάνει διάνυσμα μονάδας (0, 1, 0) |
| static [UnitZ](../../aspose.threed.utilities/vector3/unitz/) { get; } | Λαμβάνει το μοναδιαίο διάνυσμα (0, 0, 1) |
| static [Zero](../../aspose.threed.utilities/vector3/zero/) { get; } | Λαμβάνει το μοναδιαίο διάνυσμα (0, 0, 0) |
| [Item](../../aspose.threed.utilities/vector3/item/) { get; set; } |  |
| [Length](../../aspose.threed.utilities/vector3/length/) { get; } | Λαμβάνει το μήκος αυτού του διανύσματος. |
| [Length2](../../aspose.threed.utilities/vector3/length2/) { get; } | Λαμβάνει το τετράγωνο του μήκους. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AngleBetween](../../aspose.threed.utilities/vector3/anglebetween/#anglebetween)(Vector3) | Υπολογίζει τη εσωτερική γωνία μεταξύ δύο κατευθύνσεων. Οι δύο κατευθύνσεις μπορούν να είναι μη κανονικοποιημένα διανύσματα |
| [AngleBetween](../../aspose.threed.utilities/vector3/anglebetween/#anglebetween_1)(Vector3, Vector3) | Υπολογίζει τη εσωτερική γωνία μεταξύ δύο κατευθύνσεων. Οι δύο κατευθύνσεις μπορούν να είναι μη κανονικοποιημένα διανύσματα |
| [CompareTo](../../aspose.threed.utilities/vector3/compareto/)(Vector3) | Συγκρίνει το τρέχον διάνυσμα με μια άλλη παρουσία. |
| [Cos](../../aspose.threed.utilities/vector3/cos/)() | Υπολογίζει το συνημίτονο σε κάθε συνιστώσα. |
| [Cross](../../aspose.threed.utilities/vector3/cross/)(Vector3) | Γινόμενο διανυσματικού δύο διανυσμάτων |
| [Dot](../../aspose.threed.utilities/vector3/dot/)(Vector3) | Λαμβάνει το εσωτερικό γινόμενο δύο διανυσμάτων |
| override [Equals](../../aspose.threed.utilities/vector3/equals/)(object) | Ελέγχει αν δύο vector3 είναι ίσα |
| override [GetHashCode](../../aspose.threed.utilities/vector3/gethashcode/)() | Λαμβάνει τον κωδικό κατακερματισμού του Vector3 |
| [Normalize](../../aspose.threed.utilities/vector3/normalize/)() | Κανονικοποιεί αυτήν την παρουσία. |
| [Set](../../aspose.threed.utilities/vector3/set/)(double, double, double) | Ορίζει τα συστατικά x/y/z σε μία κλήση. |
| [Sin](../../aspose.threed.utilities/vector3/sin/)() | Υπολογίζει το ημίτονο σε κάθε συνιστώσα. |
| override [ToString](../../aspose.threed.utilities/vector3/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει το τρέχον `Vector3`. |
| [operator +](../../aspose.threed.utilities/vector3/op_addition/) | Υπερφόρτωση τελεστή για + |
| [operator /](../../aspose.threed.utilities/vector3/op_division/#op_division_1) | Υπερφόρτωση τελεστή για / (2 τελεστές) |
| [operator ==](../../aspose.threed.utilities/vector3/op_equality/) | Τελεστής ισότητας για Vector3 |
| [explicit operator](../../aspose.threed.utilities/vector3/op_explicit/) |  |
| [operator !=](../../aspose.threed.utilities/vector3/op_inequality/) | Τελεστής ανισότητας για Vector3 |
| [operator *](../../aspose.threed.utilities/vector3/op_multiply/#op_multiply) | Υπερφόρτωση τελεστή για * (3 τελεστές) |
| [operator -](../../aspose.threed.utilities/vector3/op_subtraction/) | Υπερφόρτωση τελεστή για - (2 τελεστές) |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| [X](../../aspose.threed.utilities/vector3/x/) | Το συστατικό x. |
| [Y](../../aspose.threed.utilities/vector3/y/) | Το συστατικό y. |
| [Z](../../aspose.threed.utilities/vector3/z/) | Το συστατικό z. |

### Δείτε επίσης

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


