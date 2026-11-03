---
title: "Κλάση PointCloud"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Entities.PointCloud. Το σύννεφο σημείων δεν περιέχει πληροφορίες τοπολογίας, αλλά μόνο τα σημεία ελέγχου και τα στοιχεία κορυφής."
type: docs
weight: 600
url: /el/net/aspose.threed.entities/pointcloud/
---
## PointCloud class

Το σύννεφο σημείων δεν περιέχει πληροφορίες τοπολογίας, αλλά μόνο τα σημεία ελέγχου και τα στοιχεία κορυφών.

```csharp
public class PointCloud : Geometry
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PointCloud](pointcloud/#constructor)() | Κατασκευαστής του `PointCloud` |
| [PointCloud](pointcloud/#constructor_1)(string) | Κατασκευαστής του `PointCloud` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | Λαμβάνει όλα τα σημεία ελέγχου |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | Λαμβάνει όλους τους παραμορφωτές που σχετίζονται με αυτή τη γεωμετρία. |
| [Dimension](../../aspose.threed.entities/pointcloud/dimension/) { get; set; } | Εάν υπάρχει τιμή διάστασης για το σύννεφο σημείων, υποδεικνύει ένα οργανωμένο σύννεφο σημείων. Χωρίς καθορισμένο μέγεθος, θεωρείται ένα ακατάστατο (αοργανωμένο) σύννεφο σημείων. Το οργανωμένο σύννεφο σημείων σημαίνει ότι έχει δομή παρόμοια με εικόνα. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [ReceiveShadows](../../aspose.threed.entities/geometry/receiveshadows/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η γεωμετρία μπορεί να λαμβάνει σκιά. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | Λαμβάνει όλα τα στοιχεία κορυφών |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | Λαμβάνει ή ορίζει αν η γεωμετρία είναι ορατή |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [FromGeometry](../../aspose.threed.entities/pointcloud/fromgeometry/#fromgeometry)(Geometry) | Δημιουργήστε ένα νέο αντικείμενο PointCloud από ένα γεωμετρικό αντικείμενο |
| static [FromGeometry](../../aspose.threed.entities/pointcloud/fromgeometry/#fromgeometry_1)(Geometry, int) | Δημιουργήστε ένα νέο αντικείμενο σύννεφου σημείων από ένα γεωμετρικό αντικείμενο. Η πυκνότητα είναι ο αριθμός των σημείων ανά μονάδα τριγώνου (Unit triangle είναι η τριγωνική με τη μέγιστη επιφάνεια από το πλέγμα). |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | Προσθέτει ένα υπάρχον στοιχείο κορυφής στην τρέχουσα γεωμετρία |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType) | Δημιουργεί ένα στοιχείο κορυφής με καθορισμένο τύπο και το προσθέτει στη γεωμετρία. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType, MappingMode, ReferenceMode) | Δημιουργεί ένα στοιχείο κορυφής με καθορισμένο τύπο και το προσθέτει στη γεωμετρία. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping) | Δημιουργεί ένα [`VertexElementUV`](../vertexelementuv/) με δεδομένο τύπο χαρτογράφησης υφής. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping, MappingMode, ReferenceMode) | Δημιουργεί ένα [`VertexElementUV`](../vertexelementuv/) με δεδομένο τύπο χαρτογράφησης υφής. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Λαμβάνει το πλαίσιο περιβάλλοντος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers/)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement/)(VertexElementType) | Λαμβάνει ένα στοιχείο κορυφής με καθορισμένο τύπο |
| override [GetEntityRendererKey](../../aspose.threed.entities/pointcloud/getentityrendererkey/)() | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον renderer |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv/)(TextureMapping) | Λαμβάνει ένα στιγμιότυπο [`VertexElementUV`](../vertexelementuv/) με δεδομένο τύπο χαρτογράφησης υφής |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

### Δείτε επίσης

* class [Geometry](../geometry/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


