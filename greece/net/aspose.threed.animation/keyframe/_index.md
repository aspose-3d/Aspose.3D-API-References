---
title: KeyFrame
second_title: Aspose.3D για Αναφορά API .NET
description: Ένα βασικό πλαίσιο ορίζεται κυρίως από έναν χρόνο και μια τιμή για ορισμένους τύπους παρεμβολής η εφαπτομένη/ένταση/πόλωση/συνέχεια χρησιμοποιείται επίσης με τον υπολογισμό της τελικής τιμής του δείγματος. κατά πλαίσιακλειδιά μεταξύ του προηγούμενου και του επόμενου keyframes Η τιμή πριν/μετά το πρώτο/τελευταίο πλαίσιοκλειδί υπολογίζεται από τοExtrapolation./extrapolation/ τάξη.
type: docs
weight: 90
url: /el/net/aspose.threed.animation/keyframe/
---
## KeyFrame class

Ένα βασικό πλαίσιο ορίζεται κυρίως από έναν χρόνο και μια τιμή, για ορισμένους τύπους παρεμβολής, η εφαπτομένη/ένταση/πόλωση/συνέχεια χρησιμοποιείται επίσης με τον υπολογισμό της τελικής τιμής του δείγματος. κατά πλαίσια-κλειδιά μεταξύ του προηγούμενου και του επόμενου key-frames Η τιμή πριν/μετά το πρώτο/τελευταίο πλαίσιο-κλειδί υπολογίζεται από το[`Extrapolation`](../extrapolation/) τάξη.

```csharp
public class KeyFrame
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [KeyFrame](keyframe/)(KeyframeSequence, double) | Δημιουργήστε ένα νέο πλαίσιο κλειδιού στο καθορισμένο curve |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Bias](../../aspose.threed.animation/keyframe/bias/) { get; set; } | Λαμβάνει ή ορίζει την προκατάληψη που χρησιμοποιείται στο TCB spline |
| [Continuity](../../aspose.threed.animation/keyframe/continuity/) { get; set; } | Λαμβάνει ή ορίζει τη συνέχεια που χρησιμοποιείται στο TCB spline |
| [Flat](../../aspose.threed.animation/keyframe/flat/) { get; set; } | Λήψη ή ρύθμιση εάν το πλαίσιο κλειδιού είναι επίπεδο. Το πλαίσιο κλειδιού πρέπει να είναι επίπεδο εάν το επόμενο ή το προηγούμενο πλαίσιο κλειδιού έχει την ίδια τιμή. Το επίπεδο πλαίσιο κλειδιού έχει επίπεδες εφαπτομένες και σταθερή παρεμβολή. |
| [IndependentTangent](../../aspose.threed.animation/keyframe/independenttangent/) { get; set; } | Οι λήψεις ή οι επόμενες σε εφαπτομένες είναι ανεξάρτητες. |
| [Interpolation](../../aspose.threed.animation/keyframe/interpolation/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο παρεμβολής του κλειδιού, το list.data[index] ορίζει τον αλγόριθμο με τον οποίο υπολογίζεται η τιμή του δείγματος. |
| [NextInTangent](../../aspose.threed.animation/keyframe/nextintangent/) { get; set; } | Λαμβάνει ή ορίζει την επόμενη εφαπτομένη σε (αριστερά) σε αυτό το πλαίσιο κλειδιού. |
| [NextInWeight](../../aspose.threed.animation/keyframe/nextinweight/) { get; set; } | Λαμβάνει ή ορίζει το επόμενο βάρος σε (αριστερά) σε αυτό το πλαίσιο κλειδιού. |
| [OutTangent](../../aspose.threed.animation/keyframe/outtangent/) { get; set; } | Λαμβάνει ή ορίζει την έξω (δεξιά) εφαπτομένη σε αυτό το πλαίσιο κλειδιού. |
| [OutWeight](../../aspose.threed.animation/keyframe/outweight/) { get; set; } | Λαμβάνει ή ρυθμίζει το βάρος (δεξιά) σε αυτό το πλαίσιο κλειδιού. |
| [StepMode](../../aspose.threed.animation/keyframe/stepmode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία βήματος του κλειδιού. Εάν ο τύπος παρεμβολής είναιConstant , list.data[index] αποφασίζει ποια τιμή του πλαισίου κλειδιού θα χρησιμοποιηθεί κατά την παρεμβολή. ΑPreviousValue σημαίνει ότι η τιμή του αριστερού πλαισίου κλειδιού θα χρησιμοποιηθεί ANextValueσημαίνει ότι η τιμή του επόμενου δεξιού πλαισίου κλειδιού θα χρησιμοποιηθεί |
| [TangentWeightMode](../../aspose.threed.animation/keyframe/tangentweightmode/) { get; set; } | Λαμβάνει ή ρυθμίζει τη λειτουργία εφαπτομενικού βάρους του κλειδιού. Η εφαπτομένη έξω ή η επόμενη σε εφαπτομένη μπορεί να προσαρμοστεί επιλέγοντας τη σωστή[`WeightedMode`](../weightedmode/) |
| [Tension](../../aspose.threed.animation/keyframe/tension/) { get; set; } | Λαμβάνει ή ρυθμίζει την τάση που χρησιμοποιείται στο TCB spline |
| [Time](../../aspose.threed.animation/keyframe/time/) { get; set; } | Λαμβάνει ή ορίζει τη χρονική θέση του πλαισίου κλειδιού list.data[index], μετρημένη σε δευτερόλεπτα. |
| [TimeIndependentTangent](../../aspose.threed.animation/keyframe/timeindependenttangent/) { get; set; } | Λαμβάνει ή ορίζει την εφαπτομένη είναι ανεξάρτητη από το χρόνο |
| [Value](../../aspose.threed.animation/keyframe/value/) { get; set; } | Λαμβάνει ή ορίζει την τιμή του καρέ-κλειδιού. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [ToString](../../aspose.threed.animation/keyframe/tostring/)() | Λαμβάνει την παράσταση συμβολοσειράς του πλαισίου κλειδιού |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* συνέλευση [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->