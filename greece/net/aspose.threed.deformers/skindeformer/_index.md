---
title: "Κλάση SkinDeformer"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Deformers.SkinDeformer. Ένας μετασχηματιστής δέρματος περιέχει πολλαπλά οστά· κάθε οστό συνδυάζει ένα μέρος της γεωμετρίας βάσει βαρών σημείων ελέγχου."
type: docs
weight: 240
url: /el/net/aspose.threed.deformers/skindeformer/
---
## SkinDeformer class

Ένας skin deformer περιέχει πολλαπλά οστά για λειτουργία, κάθε οστό συνδυάζει ένα μέρος της γεωμετρίας βάσει των βαρών των σημείων ελέγχου.

```csharp
public class SkinDeformer : Deformer
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SkinDeformer](skindeformer/#constructor)() | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `SkinDeformer`. |
| [SkinDeformer](skindeformer/#constructor_1)(string) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `SkinDeformer`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Bones](../../aspose.threed.deformers/skindeformer/bones/) { get; } | Λαμβάνει όλα τα οστά που περιέχει ο μετασχηματιστής δέρματος |
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


