---
title: "Κλάση AnimationChannel"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Animation.AnimationChannel κλάση. Ένα κανάλι αντιστοιχίζει το πεδίο συνιστώσας ιδιοτήτων σε ένα σύνολο ακολουθιών keyframe"
type: docs
weight: 20
url: /el/net/aspose.threed.animation/animationchannel/
---
## AnimationChannel class

Ένα κανάλι αντιστοιχίζει το πεδίο συνιστώσας της ιδιότητας σε ένα σύνολο ακολουθιών keyframe

```csharp
public class AnimationChannel : KeyframeSequence
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BindPoint](../../aspose.threed.animation/keyframesequence/bindpoint/) { get; } | Αποκτά το σημείο σύνδεσης ιδιότητας που κατέχει αυτή η καμπύλη. |
| [ComponentType](../../aspose.threed.animation/animationchannel/componenttype/) { get; } | Λαμβάνει τον τύπο του πεδίου συνιστώσας |
| [DefaultValue](../../aspose.threed.animation/animationchannel/defaultvalue/) { get; set; } | Λαμβάνει ή ορίζει την Default τιμή του καναλιού. Εάν ένα κανάλι δεν έχει συνδεδεμένες ακολουθίες keyframe, η προεπιλεγμένη τιμή θα χρησιμοποιηθεί κατά την αξιολόγηση της animation. Ένα πραγματικό σενάριο: Η animation αναπαριστά μόνο τη συντεταγμένη x ενός κόμβου, οι y και z δεν αλλάζουν, τότε η προεπιλεγμένη τιμή θα χρησιμοποιηθεί κατά την πλήρη αξιολόγηση της μετάφρασης. |
| [KeyFrames](../../aspose.threed.animation/keyframesequence/keyframes/) { get; } | Αποκτά τα key frames αυτής της καμπύλης. |
| [KeyframeSequence](../../aspose.threed.animation/animationchannel/keyframesequence/) { get; set; } | Λαμβάνει τη συνδεδεμένη ακολουθία keyframe μέσα σε αυτό το κανάλι |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [PostBehavior](../../aspose.threed.animation/keyframesequence/postbehavior/) { get; } | Αποκτά τη μεταγενέστερη συμπεριφορά που υποδεικνύει τι πρέπει να είναι η δειγματοληπτική τιμή μετά το τελευταίο key frame. |
| [PreBehavior](../../aspose.threed.animation/keyframesequence/prebehavior/) { get; } | Αποκτά τη προγενέστερη συμπεριφορά που υποδεικνύει τι πρέπει να είναι η δειγματοληπτική τιμή πριν το πρώτο key. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Add](../../aspose.threed.animation/keyframesequence/add/)(double, float) | Δημιουργήστε ένα νέο key frame με την καθορισμένη τιμή. |
| [Add](../../aspose.threed.animation/keyframesequence/add/)(double, float, Interpolation) | Δημιουργήστε ένα νέο key frame με την καθορισμένη τιμή. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetEnumerator](../../aspose.threed.animation/keyframesequence/getenumerator/)() | Αποκτά τον απαριθμητή για τη διαπέραση όλων των key frames. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [Reset](../../aspose.threed.animation/keyframesequence/reset/)() | Αφαιρεί όλα τα key frames και επαναφέρει τις μεταγενέστερες/προγενέστερες συμπεριφορές. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

### Δείτε επίσης

* class [KeyframeSequence](../keyframesequence/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


