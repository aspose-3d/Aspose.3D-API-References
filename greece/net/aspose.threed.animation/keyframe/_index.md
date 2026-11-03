---
title: "Κλάση KeyFrame"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Animation.KeyFrame class. Ένα καρέ‑κλειδί ορίζεται κυρίως από χρόνο και τιμή για ορισμένους τύπους παρεμβολής· η εφαπτόμενη/τάση/προδιάθεση/συνέχεια χρησιμοποιείται επίσης για τον υπολογισμό της τελικής δειγματοληπτικής τιμής. Οι δειγματοληπτικές τιμές σε θέση χρόνου που δεν είναι καρέ‑κλειδί παρεμβάλλονται από τα καρέ‑κλειδιά μεταξύ του προηγούμενου και του επόμενου καρέ‑κλειδιού. Η τιμή πριν/μετά το πρώτο/τελευταίο καρέ‑κλειδί υπολογίζεται από την κλάση Extrapolation."
type: docs
weight: 90
url: /el/net/aspose.threed.animation/keyframe/
---
## KeyFrame class

Ένα καρέ‑κλειδί ορίζεται κυρίως από χρόνο και τιμή· για ορισμένους τύπους παρεμβολής, η εφαπτόμενη/τάση/προδιάθεση/συνέχεια χρησιμοποιείται επίσης για τον υπολογισμό της τελικής δειγματοληπτικής τιμής. Οι δειγματοληπτικές τιμές σε θέση χρόνου που δεν είναι καρέ‑κλειδί παρεμβάλλονται από τα καρέ‑κλειδιά μεταξύ του προηγούμενου και του επόμενου καρέ‑κλειδιού. Η τιμή πριν/μετά το πρώτο/τελευταίο καρέ‑κλειδί υπολογίζεται από την κλάση [`Extrapolation`](../extrapolation/).

```csharp
public class KeyFrame
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [KeyFrame](keyframe/)(KeyframeSequence, double) | Δημιουργήστε ένα νέο καρέ‑κλειδί στην καθορισμένη καμπύλη. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Bias](../../aspose.threed.animation/keyframe/bias/) { get; set; } | Λαμβάνει ή ορίζει την προδιάθεση που χρησιμοποιείται στην καμπύλη TCB. |
| [Continuity](../../aspose.threed.animation/keyframe/continuity/) { get; set; } | Λαμβάνει ή ορίζει τη συνέχεια που χρησιμοποιείται στην καμπύλη TCB. |
| [Flat](../../aspose.threed.animation/keyframe/flat/) { get; set; } | Λάβετε ή ορίστε αν το καρέ‑κλειδί είναι επίπεδο. Το καρέ‑κλειδί πρέπει να είναι επίπεδο εάν το επόμενο ή το προηγούμενο καρέ‑κλειδί έχει την ίδια τιμή. Ένα επίπεδο καρέ‑κλειδί έχει επίπεδες εφαπτόμενες και σταθερή παρεμβολή. |
| [IndependentTangent](../../aspose.threed.animation/keyframe/independenttangent/) { get; set; } | Λαμβάνει ή ορίζει ότι οι εξωτερικές και οι επόμενες εσωτερικές εφαπτόμενες είναι ανεξάρτητες. |
| [Interpolation](../../aspose.threed.animation/keyframe/interpolation/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο παρεμβολής του καρέ‑κλειδιού· η list.data[index] ορίζει τον αλγόριθμο με τον οποίο υπολογίζεται η δειγματοληπτική τιμή. |
| [NextInTangent](../../aspose.threed.animation/keyframe/nextintangent/) { get; set; } | Λαμβάνει ή ορίζει την επόμενη εσωτερική (αριστερή) εφαπτόμενη σε αυτό το καρέ‑κλειδί. |
| [NextInWeight](../../aspose.threed.animation/keyframe/nextinweight/) { get; set; } | Λαμβάνει ή ορίζει το επόμενο εσωτερικό (αριστερό) βάρος σε αυτό το καρέ‑κλειδί. |
| [OutTangent](../../aspose.threed.animation/keyframe/outtangent/) { get; set; } | Λαμβάνει ή ορίζει την εξωτερική (δεξιά) εφαπτόμενη σε αυτό το καρέ‑κλειδί. |
| [OutWeight](../../aspose.threed.animation/keyframe/outweight/) { get; set; } | Λαμβάνει ή ορίζει το εξωτερικό (δεξί) βάρος σε αυτό το καρέ‑κλειδί. |
| [StepMode](../../aspose.threed.animation/keyframe/stepmode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία βήματος του καρέ‑κλειδιού. Εάν ο τύπος παρεμβολής είναι Constant, η list.data[index] αποφασίζει ποια τιμή καρέ‑κλειδιού θα χρησιμοποιηθεί κατά την παρεμβολή. Μια PreviousValue σημαίνει ότι θα χρησιμοποιηθεί η τιμή του αριστερού καρέ‑κλειδιού. Μια NextValue σημαίνει ότι θα χρησιμοποιηθεί η τιμή του επόμενου δεξιού καρέ‑κλειδιού. |
| [TangentWeightMode](../../aspose.threed.animation/keyframe/tangentweightmode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία βάρους εφαπτομένης του καρέ‑κλειδιού. Η εξωτερική εφαπτόμενη ή η επόμενη εσωτερική εφαπτόμενη μπορεί να προσαρμοστεί επιλέγοντας τη σωστή [`WeightedMode`](../weightedmode/). |
| [Tension](../../aspose.threed.animation/keyframe/tension/) { get; set; } | Λαμβάνει ή ορίζει την τάση που χρησιμοποιείται στην καμπύλη TCB. |
| [Time](../../aspose.threed.animation/keyframe/time/) { get; set; } | Λαμβάνει ή ορίζει τη χρονική θέση του καρέ‑κλειδιού list.data[index], μετρημένη σε δευτερόλεπτα. |
| [TimeIndependentTangent](../../aspose.threed.animation/keyframe/timeindependenttangent/) { get; set; } | Λαμβάνει ή ορίζει ότι η εφαπτόμενη είναι ανεξάρτητη του χρόνου. |
| [Value](../../aspose.threed.animation/keyframe/value/) { get; set; } | Λαμβάνει ή ορίζει την τιμή του key-frame. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [ToString](../../aspose.threed.animation/keyframe/tostring/)() | Λαμβάνει την αναπαράσταση συμβολοσειράς του key frame |

### Δείτε επίσης

* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


