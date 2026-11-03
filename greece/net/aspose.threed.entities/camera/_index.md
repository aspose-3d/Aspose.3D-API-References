---
title: "Κλάση Camera"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Entities.Camera. Η κάμερα περιγράφει το σημείο ματιού του θεατή που κοιτάζει τη σκηνή."
type: docs
weight: 300
url: /el/net/aspose.threed.entities/camera/
---
## Camera class

Η camera περιγράφει το σημείο ματιού του θεατή που κοιτάζει τη σκηνή.

```csharp
public class Camera : Frustum
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Camera](camera/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `Camera`. |
| [Camera](camera/#constructor_1)(ProjectionType) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Camera`. |
| [Camera](camera/#constructor_2)(string) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Camera`. |
| [Camera](camera/#constructor_3)(string, ProjectionType) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Camera`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ApertureMode](../../aspose.threed.entities/camera/aperturemode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία διαφράγματος της κάμερας. |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | Λαμβάνει ή ορίζει την αναλογία διαστάσεων του προοπτικού |
| [AspectRatio](../../aspose.threed.entities/camera/aspectratio/) { get; set; } | Λαμβάνει ή ορίζει την αναλογία διαστάσεων του επιπέδου προβολής. |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | Λαμβάνει ή ορίζει την κατεύθυνση προς την οποία κοιτάζει η κάμερα. Οι αλλαγές σε αυτήν την ιδιότητα θα επηρεάσουν επίσης το [`LookAt`](../frustum/lookat/) και το [`Target`](../frustum/target/). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | Λαμβάνει ή ορίζει την απόσταση του απομακρυσμένου επιπέδου του θόλου. |
| [FieldOfView](../../aspose.threed.entities/camera/fieldofview/) { get; set; } | Λαμβάνει ή ορίζει το πεδίο θέασης της κάμερας σε μοίρες· αυτή η ιδιότητα χρησιμοποιείται μόνο όταν το ApertureMode είναι Οριζόντιο ή Κατακόρυφο. |
| [FieldOfViewX](../../aspose.threed.entities/camera/fieldofviewx/) { get; set; } | Λαμβάνει ή ορίζει το οριζόντιο πεδίο θέασης της κάμερας σε μοίρες· αυτή η ιδιότητα χρησιμοποιείται μόνο όταν το ApertureMode είναι HorizAndVert. |
| [FieldOfViewY](../../aspose.threed.entities/camera/fieldofviewy/) { get; set; } | Λαμβάνει ή ορίζει το κατακόρυφο πεδίο θέασης της κάμερας σε μοίρες· αυτή η ιδιότητα χρησιμοποιείται μόνο όταν το ApertureMode είναι HorizAndVert. |
| [Height](../../aspose.threed.entities/camera/height/) { get; set; } | Λαμβάνει ή ορίζει το ύψος του επιπέδου προβολής σε ίντσες. |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | Λαμβάνει ή ορίζει τη θέση ενδιαφέροντος που κοιτάζει η κάμερα. |
| [Magnification](../../aspose.threed.entities/camera/magnification/) { get; set; } | Λαμβάνει ή ορίζει το μεγεθυντικό παράγοντα που χρησιμοποιείται σε ορθογραφική κάμερα. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | Λαμβάνει ή ορίζει την απόσταση του κοντινού επιπέδου του θόλου. |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | Λαμβάνει ή ορίζει το ύψος όταν ο θόλος βρίσκεται σε ορθογώνια προβολή. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [ProjectionType](../../aspose.threed.entities/camera/projectiontype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο προβολής της κάμερας. Από προεπιλογή χρησιμοποιείται η προοπτική προβολή. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία προσανατολισμού του θόλου. Αυτή η ιδιότητα λειτουργεί μόνο όταν το [`Target`](../frustum/target/) είναι null. Εάν η τιμή είναι FixedTarget, η κατεύθυνση υπολογίζεται πάντα από την ιδιότητα [`LookAt`](../frustum/lookat/). Διαφορετικά, το [`LookAt`](../frustum/lookat/) υπολογίζεται πάντα από το [`Direction`](../frustum/direction/). |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | Λαμβάνει ή ορίζει τον στόχο προς τον οποίο κοιτάζει η κάμερα. Εάν ο χρήστης υποστηρίζει αυτήν την ιδιότητα, πρέπει να είναι πριν από την ιδιότητα [`LookAt`](../frustum/lookat/). |
| [Up](../../aspose.threed.entities/frustum/up/) { get; set; } | Λαμβάνει ή ορίζει την κατεύθυνση προς τα πάνω της κάμερας. |
| [Width](../../aspose.threed.entities/camera/width/) { get; set; } | Λαμβάνει ή ορίζει το πλάτος του επιπέδου προβολής σε ίντσες. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Λαμβάνει το πλαίσιο περιβάλλοντος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον renderer |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [MoveForward](../../aspose.threed.entities/camera/moveforward/)(double) | Μετακινήστε την κάμερα προς τα εμπρός προς την κατεύθυνσή της ή τον στόχο. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

### Δείτε επίσης

* class [Frustum](../frustum/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


