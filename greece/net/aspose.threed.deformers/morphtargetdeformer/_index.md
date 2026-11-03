---
title: "Κλάση MorphTargetDeformer"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Deformers.MorphTargetDeformer class. Το MorphTargetDeformer παρέχει animation pervertex. Το MorphTargetDeformer οργανώνει όλα τα στόχους μέσω MorphTargetChannel, κάθε κανάλι μπορεί να οργανώσει πολλαπλούς στόχους. Μία κοινή χρήση του morph target deformer είναι η εφαρμογή εκφράσεων προσώπου σε έναν χαρακτήρα. Περισσότερες λεπτομέρειες μπορούν να βρεθούν στο https//en.wikipedia.org/wiki/Morph_target_animation"
type: docs
weight: 230
url: /el/net/aspose.threed.deformers/morphtargetdeformer/
---
## MorphTargetDeformer class

Το MorphTargetDeformer παρέχει animation per-vertex. Το MorphTargetDeformer οργανώνει όλα τα στόχους μέσω [`MorphTargetChannel`](../morphtargetchannel/), κάθε κανάλι μπορεί να οργανώσει πολλαπλούς στόχους. Μία κοινή χρήση του morph target deformer είναι η εφαρμογή εκφράσεων προσώπου σε έναν χαρακτήρα. Περισσότερες λεπτομέρειες μπορούν να βρεθούν στο https://en.wikipedia.org/wiki/Morph_target_animation

```csharp
public class MorphTargetDeformer : Deformer
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MorphTargetDeformer](morphtargetdeformer/#constructor)() | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `MorphTargetDeformer`. |
| [MorphTargetDeformer](morphtargetdeformer/#constructor_1)(string) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `MorphTargetDeformer`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Channels](../../aspose.threed.deformers/morphtargetdeformer/channels/) { get; } | Λαμβάνει όλα τα κανάλια που περιέχονται σε αυτόν τον deformer |
| [Item](../../aspose.threed.deformers/morphtargetdeformer/item/) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [Owner](../../aspose.threed.deformers/deformer/owner/) { get; } | Λαμβάνει τη γεωμετρία που κατέχει αυτόν τον μετασχηματιστή |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

### Δείτε επίσης

* class [Deformer](../deformer/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


