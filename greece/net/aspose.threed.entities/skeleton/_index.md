---
title: "Κλάση Skeleton"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Entities.Skeleton. Το Skeleton χρησιμοποιείται κυρίως από λογισμικό CAD για να βοηθήσει τον σχεδιαστή να χειριστεί τη μετασχηματισμό της σκελετική δομής, συνήθως είναι άχρηστο εκτός των λογισμικών CAD. Για να λειτουργεί η ιεραρχία του σκελετού ως ένα αντικείμενο στο λογισμικό CAD, είναι απαραίτητο να σημειωθεί ο κορυφαίος κόμβος Skeleton ως ρίζα ορίζοντας το Type σε Skeleton και όλα τα παιδιά σε Bone."
type: docs
weight: 710
url: /el/net/aspose.threed.entities/skeleton/
---
## Skeleton class

Το `Skeleton` χρησιμοποιείται κυρίως από λογισμικό CAD για να βοηθήσει τον σχεδιαστή να χειριστεί τη μετασχηματισμό της σκελετική δομής, είναι συνήθως άχρηστο εκτός των λογισμικών CAD. Για να λειτουργεί η ιεραρχία του σκελετού ως ένα αντικείμενο στο λογισμικό CAD, είναι απαραίτητο να σημειωθεί ο κορυφαίος κόμβος `Skeleton` ως ρίζα ορίζοντας το [`Type`](./type/) σε Skeleton, και όλα τα παιδιά σε Bone.

```csharp
public class Skeleton : Entity
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Skeleton](skeleton/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `Skeleton`. |
| [Skeleton](skeleton/#constructor_1)(string) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Skeleton`. |
| [Skeleton](skeleton/#constructor_2)(string, SkeletonType) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Skeleton`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [Size](../../aspose.threed.entities/skeleton/size/) { get; set; } | Λαμβάνει ή ορίζει το μέγεθος του κόμβου άκρου που χρησιμοποιείται σε λογισμικό CAD για την αναπαράσταση του μεγέθους του οστού. |
| [Type](../../aspose.threed.entities/skeleton/type/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο του σκελετού. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Λαμβάνει το πλαίσιο περιβάλλοντος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον renderer |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

### Δείτε επίσης

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


