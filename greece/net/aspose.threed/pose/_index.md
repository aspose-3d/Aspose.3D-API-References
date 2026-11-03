---
title: "Κλάση Pose"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Pose. Η θέση χρησιμοποιείται για την αποθήκευση του πίνακα μετασχηματισμού όταν η γεωμετρία είναι ενσωματωμένη. Η θέση είναι ένα σύνολο από BonePose, κάθε BonePose αποθηκεύει τις συγκεκριμένες πληροφορίες μετασχηματισμού του κόμβου οστού."
type: docs
weight: 1650
url: /el/net/aspose.threed/pose/
---
## Pose class

Η θέση χρησιμοποιείται για την αποθήκευση του πίνακα μετασχηματισμού όταν η γεωμετρία είναι ενσωματωμένη. Η θέση είναι ένα σύνολο από [`BonePose`](../bonepose/), κάθε [`BonePose`](../bonepose/) αποθηκεύει τις συγκεκριμένες πληροφορίες μετασχηματισμού του κόμβου οστού.

```csharp
public class Pose : A3DObject
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Pose](pose/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `Pose`. |
| [Pose](pose/#constructor_1)(string) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Pose`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BonePoses](../../aspose.threed/pose/boneposes/) { get; } | Λαμβάνει όλα τα [`BonePose`](../bonepose/). |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [PoseType](../../aspose.threed/pose/posetype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο της θέσης. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose)(Node, Matrix4) | Αποθηκεύει τον πίνακα μετασχηματισμού της θέσης για τον δεδομένο κόμβο οστού. Ο παγκόσμιος πίνακας μετασχηματισμού υπονοείται. |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose_1)(Node, Matrix4, bool) | Αποθηκεύει τον πίνακα μετασχηματισμού της θέσης για τον δεδομένο κόμβο οστού. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

### Δείτε επίσης

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


