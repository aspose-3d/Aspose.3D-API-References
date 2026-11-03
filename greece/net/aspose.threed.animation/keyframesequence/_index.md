---
title: "Κλάση KeyframeSequence"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Animation.KeyframeSequence. Η ακολουθία των keyframes περιγράφει τη μεταβολή μιας δειγματοληπτικής τιμής με την πάροδο του χρόνου."
type: docs
weight: 100
url: /el/net/aspose.threed.animation/keyframesequence/
---
## KeyframeSequence class

Η ακολουθία των key-frames, περιγράφει τη μετασχηματισμό μιας δειγματοληπτικής τιμής με την πάροδο του χρόνου.

```csharp
public class KeyframeSequence : A3DObject, IEnumerable<KeyFrame>
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [KeyframeSequence](keyframesequence/#constructor)() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `KeyframeSequence`. |
| [KeyframeSequence](keyframesequence/#constructor_1)(string) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `KeyframeSequence`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BindPoint](../../aspose.threed.animation/keyframesequence/bindpoint/) { get; } | Αποκτά το σημείο σύνδεσης ιδιότητας που κατέχει αυτή η καμπύλη. |
| [KeyFrames](../../aspose.threed.animation/keyframesequence/keyframes/) { get; } | Αποκτά τα key frames αυτής της καμπύλης. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [PostBehavior](../../aspose.threed.animation/keyframesequence/postbehavior/) { get; } | Αποκτά τη μεταγενέστερη συμπεριφορά που υποδεικνύει τι πρέπει να είναι η δειγματοληπτική τιμή μετά το τελευταίο key frame. |
| [PreBehavior](../../aspose.threed.animation/keyframesequence/prebehavior/) { get; } | Αποκτά τη προγενέστερη συμπεριφορά που υποδεικνύει τι πρέπει να είναι η δειγματοληπτική τιμή πριν το πρώτο key. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Add](../../aspose.threed.animation/keyframesequence/add/#add)(double, float) | Δημιουργήστε ένα νέο key frame με την καθορισμένη τιμή. |
| [Add](../../aspose.threed.animation/keyframesequence/add/#add_1)(double, float, Interpolation) | Δημιουργήστε ένα νέο key frame με την καθορισμένη τιμή. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetEnumerator](../../aspose.threed.animation/keyframesequence/getenumerator/)() | Αποκτά τον απαριθμητή για τη διαπέραση όλων των key frames. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [Reset](../../aspose.threed.animation/keyframesequence/reset/)() | Αφαιρεί όλα τα key frames και επαναφέρει τις μεταγενέστερες/προγενέστερες συμπεριφορές. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

### Δείτε επίσης

* class [A3DObject](../../aspose.threed/a3dobject/)
* class [KeyFrame](../keyframe/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


