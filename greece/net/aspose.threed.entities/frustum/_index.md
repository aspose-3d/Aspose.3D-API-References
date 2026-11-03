---
title: "Κλάση Frustum"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Entities.Frustum. Η βασική κλάση του Camera και του Light"
type: docs
weight: 400
url: /el/net/aspose.threed.entities/frustum/
---
## Frustum class

Η βασική κλάση του [`Camera`](../camera/) και του [`Light`](../light/)

```csharp
public abstract class Frustum : Entity, IOrientable
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | Λαμβάνει ή ορίζει την αναλογία διαστάσεων του προοπτικού |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | Λαμβάνει ή ορίζει την κατεύθυνση προς την οποία κοιτάζει η κάμερα. Οι αλλαγές σε αυτήν την ιδιότητα θα επηρεάσουν επίσης το [`LookAt`](./lookat/) και το [`Target`](./target/). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | Λαμβάνει ή ορίζει την απόσταση του απομακρυσμένου επιπέδου του θόλου. |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | Λαμβάνει ή ορίζει τη θέση ενδιαφέροντος που κοιτάζει η κάμερα. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | Λαμβάνει ή ορίζει την απόσταση του κοντινού επιπέδου του θόλου. |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | Λαμβάνει ή ορίζει το ύψος όταν ο θόλος βρίσκεται σε ορθογώνια προβολή. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία προσανατολισμού του frustum. Αυτή η ιδιότητα λειτουργεί μόνο όταν το [`Target`](./target/) είναι null. Εάν η τιμή είναι FixedTarget, η κατεύθυνση υπολογίζεται πάντα από την ιδιότητα [`LookAt`](./lookat/). Διαφορετικά, το [`LookAt`](./lookat/) υπολογίζεται πάντα από το [`Direction`](./direction/). |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | Λαμβάνει ή ορίζει τον στόχο προς τον οποίο κοιτάζει η κάμερα. Εάν ο χρήστης υποστηρίζει αυτήν την ιδιότητα, θα πρέπει να είναι πριν από την ιδιότητα [`LookAt`](./lookat/). |
| [Up](../../aspose.threed.entities/frustum/up/) { get; set; } | Λαμβάνει ή ορίζει την κατεύθυνση προς τα πάνω της κάμερας. |

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
* interface [IOrientable](../iorientable/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


