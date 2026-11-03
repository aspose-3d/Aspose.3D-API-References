---
title: "Κλάση Group"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Group κλάση. Ένα Group αντιπροσωπεύει τις λογικές σχέσεις του Node."
type: docs
weight: 1570
url: /el/net/aspose.threed/group/
---
## Group class

Ένα `Group` αντιπροσωπεύει τις λογικές σχέσεις του [`Node`](../node/).

```csharp
public class Group : A3DObject
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Group](group/)(string) | Δημιουργήστε μια νέα παρουσία του `Group` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Groups](../../aspose.threed/group/groups/) { get; } | Υπο-ομάδες |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [Nodes](../../aspose.threed/group/nodes/) { get; } | Οι κόμβοι σε αυτήν την ομάδα |
| [Parent](../../aspose.threed/group/parent/) { get; } | Γονική ομάδα της τρέχουσας ομάδας |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |
| override [ToString](../../aspose.threed/group/tostring/)() | Λαμβάνει την αναπαράσταση συμβολοσειράς του `Group` |

### Δείτε επίσης

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


