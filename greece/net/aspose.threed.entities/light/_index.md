---
title: "Κλάση Light"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Entities.Light. Το φως φωτίζει τη σκηνή"
type: docs
weight: 460
url: /el/net/aspose.threed.entities/light/
---
## Light class

Το φως φωτίζει τη σκηνή.

Ο τύπος για τον υπολογισμό της συνολικής εξασθένισης του φωτός είναι: `A = ConstantAttenuation + (Dist * LinearAttenuation) + ((Dist^2) * QuadraticAttenuation)`

```csharp
public class Light : Frustum
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Light](light/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `Light`. |
| [Light](light/#constructor_1)(string) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Light`. |
| [Light](light/#constructor_2)(string, LightType) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Light`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | Λαμβάνει ή ορίζει την αναλογία διαστάσεων του προοπτικού |
| [CastLight](../../aspose.threed.entities/light/castlight/) { get; set; } | Λαμβάνει ή ορίζει αν η τρέχουσα παρουσία φωτός μπορεί να φωτίσει άλλα αντικείμενα. |
| [CastShadows](../../aspose.threed.entities/light/castshadows/) { get; set; } | Λαμβάνει ή ορίζει αν το φως μπορεί να ρίξει σκιές σε άλλα αντικείμενα. |
| [Color](../../aspose.threed.entities/light/color/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα του φωτός |
| [ConstantAttenuation](../../aspose.threed.entities/light/constantattenuation/) { get; set; } | Λαμβάνει ή ορίζει τη σταθερή απόσβεση για τον υπολογισμό της συνολικής απόσβεσης του φωτός |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | Λαμβάνει ή ορίζει την κατεύθυνση προς την οποία κοιτάζει η κάμερα. Οι αλλαγές σε αυτήν την ιδιότητα θα επηρεάσουν επίσης το [`LookAt`](../frustum/lookat/) και το [`Target`](../frustum/target/). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| [Falloff](../../aspose.threed.entities/light/falloff/) { get; set; } | Λαμβάνει ή ορίζει τη γωνία κώνου εξασθένισης (σε μοίρες). |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | Λαμβάνει ή ορίζει την απόσταση του απομακρυσμένου επιπέδου του θόλου. |
| [HotSpot](../../aspose.threed.entities/light/hotspot/) { get; set; } | Λαμβάνει ή ορίζει τη γωνία κώνου του σημείου εστίασης (σε μοίρες). |
| [Intensity](../../aspose.threed.entities/light/intensity/) { get; set; } | Λαμβάνει ή ορίζει την ένταση του φωτός, η προεπιλεγμένη τιμή είναι 100 |
| [LightType](../../aspose.threed.entities/light/lighttype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο του φωτός |
| [LinearAttenuation](../../aspose.threed.entities/light/linearattenuation/) { get; set; } | Λαμβάνει ή ορίζει τη γραμμική απόσβεση για τον υπολογισμό της συνολικής απόσβεσης του φωτός |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | Λαμβάνει ή ορίζει τη θέση ενδιαφέροντος που κοιτάζει η κάμερα. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | Λαμβάνει ή ορίζει την απόσταση του κοντινού επιπέδου του θόλου. |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | Λαμβάνει ή ορίζει το ύψος όταν ο θόλος βρίσκεται σε ορθογώνια προβολή. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [QuadraticAttenuation](../../aspose.threed.entities/light/quadraticattenuation/) { get; set; } | Λαμβάνει ή ορίζει τη τετραγωνική απόσβεση για τον υπολογισμό της συνολικής απόσβεσης του φωτός |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία προσανατολισμού του θόλου. Αυτή η ιδιότητα λειτουργεί μόνο όταν το [`Target`](../frustum/target/) είναι null. Εάν η τιμή είναι FixedTarget, η κατεύθυνση υπολογίζεται πάντα από την ιδιότητα [`LookAt`](../frustum/lookat/). Διαφορετικά, το [`LookAt`](../frustum/lookat/) υπολογίζεται πάντα από το [`Direction`](../frustum/direction/). |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [ShadowColor](../../aspose.threed.entities/light/shadowcolor/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα της σκιάς. |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | Λαμβάνει ή ορίζει τον στόχο προς τον οποίο κοιτάζει η κάμερα. Εάν ο χρήστης υποστηρίζει αυτήν την ιδιότητα, πρέπει να είναι πριν από την ιδιότητα [`LookAt`](../frustum/lookat/). |
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

* class [Frustum](../frustum/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


