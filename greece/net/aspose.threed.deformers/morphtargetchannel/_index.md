---
title: "Κλάση MorphTargetChannel"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Deformers.MorphTargetChannel class. Ένα MorphTargetChannel χρησιμοποιείται από MorphTargetDeformer για την οργάνωση των γεωμετριών-στόχων. Ορισμένες μορφές αρχείων όπως το FBX υποστηρίζουν πολλαπλά κανάλια παράλληλα"
type: docs
weight: 220
url: /el/net/aspose.threed.deformers/morphtargetchannel/
---
## MorphTargetChannel class

Ένα MorphTargetChannel χρησιμοποιείται από το [`MorphTargetDeformer`](../morphtargetdeformer/) για την οργάνωση των γεωμετριών-στόχων. Ορισμένες μορφές αρχείων όπως το FBX υποστηρίζουν πολλαπλά κανάλια παράλληλα.

```csharp
public class MorphTargetChannel : A3DObject
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MorphTargetChannel](morphtargetchannel/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `MorphTargetChannel`. |
| [MorphTargetChannel](morphtargetchannel/#constructor_1)(string) | Αρχικοποιεί μια νέα παρουσία της κλάσης `MorphTargetChannel`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ChannelWeight](../../aspose.threed.deformers/morphtargetchannel/channelweight/) { get; set; } | Λαμβάνει ή ορίζει το βάρος του παραμορφωτή για αυτό το κανάλι. Το βάρος είναι μεταξύ 0.0 και 1.0 |
| [Item](../../aspose.threed.deformers/morphtargetchannel/item/) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Targets](../../aspose.threed.deformers/morphtargetchannel/targets/) { get; } | Λαμβάνει όλους τους στόχους που σχετίζονται με το κανάλι. |
| [Weights](../../aspose.threed.deformers/morphtargetchannel/weights/) { get; } | Λαμβάνει τις πλήρεις τιμές βάρους των γεωμετριών-στόχων. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [GetWeight](../../aspose.threed.deformers/morphtargetchannel/getweight/)(Shape) | Λαμβάνει το βάρος για τον καθορισμένο στόχο, εάν ο στόχος δεν ανήκει σε αυτό το κανάλι, επιστρέφεται η προεπιλεγμένη τιμή 0. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |
| [SetWeight](../../aspose.threed.deformers/morphtargetchannel/setweight/)(Shape, double) | Ορίζει το βάρος για τον καθορισμένο στόχο, η προεπιλεγμένη τιμή είναι 1, το εύρος πρέπει να είναι μεταξύ 0~1. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [DefaultWeight](../../aspose.threed.deformers/morphtargetchannel/defaultweight/) | Προεπιλεγμένο βάρος για το morph target. |

## Παρατηρήσεις

Το βάρος είναι μεταξύ 0 και 1.0, και το προεπιλεγμένο βάρος για το στόχο είναι 0.0;

### Δείτε επίσης

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


