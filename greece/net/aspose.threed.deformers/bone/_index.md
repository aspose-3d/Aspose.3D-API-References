---
title: "Κλάση Bone"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Deformers.Bone class. Ένα bone ορίζει το υποσύνολο των σημείων ελέγχου της γεωμετρίας και καθορίζει το βάρος ανάμειξης για κάθε σημείο ελέγχου. Το αντικείμενο Bone δεν μπορεί να χρησιμοποιηθεί άμεσα· μια παρουσία SkinDeformer χρησιμοποιείται για την παραμόρφωση της γεωμετρίας και το SkinDeformer περιλαμβάνει ένα σύνολο από bones, κάθε bone συνδεδεμένο με έναν κόμβο. ΣΗΜΕΙΩΣΗ: Ένα σημείο ελέγχου μιας γεωμετρίας μπορεί να δεσμευτεί σε περισσότερα από ένα Bones."
type: docs
weight: 190
url: /el/net/aspose.threed.deformers/bone/
---
## Bone class

Ένα bone ορίζει το υποσύνολο των σημείων ελέγχου της γεωμετρίας και καθορίζει το βάρος ανάμειξης για κάθε σημείο ελέγχου. Το αντικείμενο `Bone` δεν μπορεί να χρησιμοποιηθεί άμεσα, μια παρουσία [`SkinDeformer`](../skindeformer/) χρησιμοποιείται για την παραμόρφωση της γεωμετρίας, και το [`SkinDeformer`](../skindeformer/) περιλαμβάνει ένα σύνολο από bones, κάθε bone συνδεδεμένο με έναν κόμβο. ΣΗΜΕΙΩΣΗ: Ένα σημείο ελέγχου μιας γεωμετρίας μπορεί να δεσμευτεί σε περισσότερα από ένα Bones.

```csharp
public class Bone : A3DObject
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Bone](bone/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `Bone`. |
| [Bone](bone/#constructor_1)(string) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Bone`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BoneTransform](../../aspose.threed.deformers/bone/bonetransform/) { get; set; } | Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού του bone. |
| [Item](../../aspose.threed.deformers/bone/item/) { get; set; } |  |
| [LinkMode](../../aspose.threed.deformers/bone/linkmode/) { get; set; } | Η λειτουργία σύνδεσης ενός οστού αναφέρεται στον τρόπο με τον οποίο ένα οστό συνδέεται ή συνδέεται με το γονικό του οστό μέσα σε μια ιεραρχική δομή. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [Node](../../aspose.threed.deformers/bone/node/) { get; set; } | Λαμβάνει ή ορίζει τον κόμβο. Ο κόμβος bone είναι το bone στο οποίο συνδέεται το δέρμα, το [`SkinDeformer`](../skindeformer/) θα χρησιμοποιήσει τον κόμβο bone για να επηρεάσει τη μετατόπιση των σημείων ελέγχου. Ο κόμβος bone συνήθως έχει ένα συνημμένο [`Skeleton`](../../aspose.threed.entities/skeleton/), αλλά δεν είναι υποχρεωτικό. Το συνημμένο [`Skeleton`](../../aspose.threed.entities/skeleton/) συνήθως χρησιμοποιείται από λογισμικό DCC για να εμφανίσει το σκελετό στον χρήστη. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Transform](../../aspose.threed.deformers/bone/transform/) { get; set; } | Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού του κόμβου που περιέχει το bone. |
| [WeightCount](../../aspose.threed.deformers/bone/weightcount/) { get; } | Λαμβάνει τον αριθμό των βαρών, αυτό επεκτείνεται αυτόματα από το [`SetWeight`](./setweight/) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [GetWeight](../../aspose.threed.deformers/bone/getweight/)(int) | Λαμβάνει το βάρος για το σημείο ελέγχου που καθορίζεται με δείκτη |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |
| [SetWeight](../../aspose.threed.deformers/bone/setweight/)(int, double) | Ορίζει το βάρος για το σημείο ελέγχου που καθορίζεται με δείκτη |

### Δείτε επίσης

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


