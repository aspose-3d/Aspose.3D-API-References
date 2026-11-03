---
title: "Κλάση Mesh"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Entities.Mesh. Ένα πλέγμα αποτελείται από πολλά πολύγωνα με n πλευρές"
type: docs
weight: 510
url: /el/net/aspose.threed.entities/mesh/
---
## Mesh class

Ένα πλέγμα αποτελείται από πολλά n-πλευρά πολύγωνα.

```csharp
public class Mesh : Geometry, IEnumerable<int[]>, IMeshConvertible
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Mesh](mesh/#constructor)() | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `Mesh`. |
| [Mesh](mesh/#constructor_4)(string) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `Mesh`. |
| [Mesh](mesh/#constructor_1)(TextureData) | Δημιουργήστε ένα πλέγμα χρησιμοποιώντας τον καθορισμένο χάρτη υψών· εάν η μορφή εικονοστοιχείων του χάρτη υψών περιέχει πολλαπλά συστατικά, το πρώτο (συνήθως το κόκκινο) συστατικό θα χρησιμοποιηθεί ως τιμή ύψους (z). Τα συστατικά x και y του σημείου ελέγχου είναι κανονικοποιημένες συντεταγμένες εικονοστοιχείου. |
| [Mesh](mesh/#constructor_2)(TextureData, Matrix4) | Δημιουργήστε ένα πλέγμα χρησιμοποιώντας τον καθορισμένο χάρτη υψών· εάν η μορφή εικονοστοιχείων του χάρτη υψών περιέχει πολλαπλά συστατικά, το πρώτο (συνήθως το κόκκινο) συστατικό θα χρησιμοποιηθεί ως τιμή ύψους (z). Τα συστατικά x και y του σημείου ελέγχου είναι κανονικοποιημένες συντεταγμένες εικονοστοιχείου. |
| [Mesh](mesh/#constructor_3)(TextureData, bool, Matrix4) | Δημιουργήστε ένα πλέγμα χρησιμοποιώντας τον καθορισμένο χάρτη υψών· εάν η μορφή εικονοστοιχείων του χάρτη υψών περιέχει πολλαπλά συστατικά, το πρώτο (συνήθως το κόκκινο) συστατικό θα χρησιμοποιηθεί ως τιμή ύψους (z). Τα συστατικά x και y του σημείου ελέγχου είναι κανονικοποιημένες συντεταγμένες εικονοστοιχείου. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | Λαμβάνει όλα τα σημεία ελέγχου |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | Λαμβάνει όλους τους παραμορφωτές που σχετίζονται με αυτή τη γεωμετρία. |
| [Edges](../../aspose.threed.entities/mesh/edges/) { get; } | Λαμβάνει τις ακμές του Mesh. Η ακμή είναι προαιρετική στο πλέγμα, επομένως μπορεί να είναι κενή. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [PolygonCount](../../aspose.threed.entities/mesh/polygoncount/) { get; } | Λαμβάνει τον αριθμό των πολυγώνων |
| [Polygons](../../aspose.threed.entities/mesh/polygons/) { get; } | Λαμβάνει τον ορισμό των πολυγώνων του πλέγματος |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [ReceiveShadows](../../aspose.threed.entities/geometry/receiveshadows/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η γεωμετρία μπορεί να λαμβάνει σκιά. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | Λαμβάνει όλα τα στοιχεία κορυφών |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | Λαμβάνει ή ορίζει αν η γεωμετρία είναι ορατή |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [DoBoolean](../../aspose.threed.entities/mesh/doboolean/)(BooleanOperation, Mesh, Matrix4?, Mesh, Matrix4?) |  |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | Προσθέτει ένα υπάρχον στοιχείο κορυφής στην τρέχουσα γεωμετρία |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType) | Δημιουργεί ένα στοιχείο κορυφής με καθορισμένο τύπο και το προσθέτει στη γεωμετρία. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType, MappingMode, ReferenceMode) | Δημιουργεί ένα στοιχείο κορυφής με καθορισμένο τύπο και το προσθέτει στη γεωμετρία. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping) | Δημιουργεί ένα [`VertexElementUV`](../vertexelementuv/) με δεδομένο τύπο χαρτογράφησης υφής. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping, MappingMode, ReferenceMode) | Δημιουργεί ένα [`VertexElementUV`](../vertexelementuv/) με δεδομένο τύπο χαρτογράφησης υφής. |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_2)(int[]) | Δημιουργεί ένα νέο πολύγωνο με όλες τις κορυφές ορισμένες στα *indices*. Για δημιουργία πολύγωνου κορυφή προς κορυφή, παρακαλώ χρησιμοποιήστε το [`PolygonBuilder`](../polygonbuilder/). |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon)(int, int, int) | Δημιουργήστε ένα πολύγωνο με 3 κορυφές (τρίγωνο) |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_3)(int[], int, int) | Δημιουργεί ένα νέο πολύγωνο με όλες τις κορυφές ορισμένες στα *indices*. Για δημιουργία πολύγωνου κορυφή προς κορυφή, παρακαλώ χρησιμοποιήστε το [`PolygonBuilder`](../polygonbuilder/). |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_1)(int, int, int, int) | Δημιουργήστε ένα πολύγωνο με 4 κορυφές (τετράπλευρο) |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Λαμβάνει το πλαίσιο περιβάλλοντος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers/)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement/)(VertexElementType) | Λαμβάνει ένα στοιχείο κορυφής με καθορισμένο τύπο |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον renderer |
| [GetEnumerator](../../aspose.threed.entities/mesh/getenumerator/)() | Λαμβάνει τον αριθμητή για κάθε εσωτερικό πολύγωνο. |
| [GetPolygonSize](../../aspose.threed.entities/mesh/getpolygonsize/)(int) | Λαμβάνει τον αριθμό κορυφών του καθορισμένου πολύγωνου. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv/)(TextureMapping) | Λαμβάνει ένα στιγμιότυπο [`VertexElementUV`](../vertexelementuv/) με δεδομένο τύπο χαρτογράφησης υφής |
| [IsManifold](../../aspose.threed.entities/mesh/ismanifold/)() | Ελέγχει αν το τρέχον πλέγμα είναι ένα manifold πλέγμα. Αυτή η λειτουργία δεν θα αποθηκεύσει στην κρυφή μνήμη το αποτέλεσμα του υπολογισμού manifold. |
| [Optimize](../../aspose.threed.entities/mesh/optimize/#optimize)(bool) | Βελτιστοποιεί τη χρήση μνήμης του πλέγματος αφαιρώντας διπλότυπα σημεία ελέγχου |
| [Optimize](../../aspose.threed.entities/mesh/optimize/#optimize_1)(bool, float, float, float) | Βελτιστοποιεί τη χρήση μνήμης του πλέγματος αφαιρώντας διπλότυπα σημεία ελέγχου |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |
| [ToMesh](../../aspose.threed.entities/mesh/tomesh/)() | Λαμβάνει το στιγμιότυπο Mesh από την τρέχουσα οντότητα. |
| [Triangulate](../../aspose.threed.entities/mesh/triangulate/)() | Επιστρέφει τριγωνοποιημένο πλέγμα |
| [operator &amp;](../../aspose.threed.entities/mesh/op_bitwiseand/) | Υπολογίζει την τομή δύο πλεγμάτων |
| [operator &#x7C;](../../aspose.threed.entities/mesh/op_bitwiseor/) | Υπολογίζει την ένωση δύο πλεγμάτων |
| [operator -](../../aspose.threed.entities/mesh/op_subtraction/) | Υπολογίστε τη διαφορά μεταξύ δύο πλεγμάτων |

## Παραδείγματα

Για να προσθέσετε ένα πολύγωνο στο πλέγμα:

```csharp
Mesh mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

Περιηγηθείτε σε όλα τα πολύγωνα στο πλέγμα:

```csharp
Mesh mesh = new Mesh();
foreach(int[] polygon in mesh)
{
    //αντιμετωπίστε το πολύγωνο
}
```

### Δείτε επίσης

* class [Geometry](../geometry/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


