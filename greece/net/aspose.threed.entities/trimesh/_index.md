---
title: "Κλάση TriMesh"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Entities.TriMesh. Ένα TriMesh περιέχει ακατέργαστα δεδομένα που μπορούν να χρησιμοποιηθούν απευθείας από την GPU. Αυτή η κλάση είναι ένα βοηθητικό εργαλείο για τη δημιουργία ενός πλέγματος που περιέχει μόνο δεδομένα ανά κορυφή."
type: docs
weight: 790
url: /el/net/aspose.threed.entities/trimesh/
---
## TriMesh class

Ένα TriMesh περιέχει ακατέργαστα δεδομένα που μπορούν να χρησιμοποιηθούν απευθείας από την GPU. Αυτή η κλάση είναι ένα βοηθητικό εργαλείο για την κατασκευή ενός πλέγματος που περιέχει μόνο δεδομένα ανά κορυφή.

```csharp
public class TriMesh : Entity, IEnumerable<Vertex>
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [TriMesh](trimesh/)(string, VertexDeclaration) | Αρχικοποιήστε ένα στιγμιότυπο του `TriMesh` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Capacity](../../aspose.threed.entities/trimesh/capacity/) { get; } | Η χωρητικότητα των προ-καθορισμένων κορυφών. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| [IndicesCount](../../aspose.threed.entities/trimesh/indicescount/) { get; } | Ο αριθμός των δεικτών σε αυτό το `TriMesh` |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [UnmergedVerticesCount](../../aspose.threed.entities/trimesh/unmergedverticescount/) { get; } | Ο αριθμός των μη συγχωνευμένων κορυφών που εισήχθησαν από το [`BeginVertex`](./beginvertex/) και το [`EndVertex`](./endvertex/). |
| [VertexDeclaration](../../aspose.threed.entities/trimesh/vertexdeclaration/) { get; } | Η διάταξη των κορυφών του `TriMesh`. |
| [VerticesCount](../../aspose.threed.entities/trimesh/verticescount/) { get; } | Ο αριθμός των κορυφών σε αυτό το `TriMesh` |
| [VerticesSizeInBytes](../../aspose.threed.entities/trimesh/verticessizeinbytes/) { get; } | Το συνολικό μέγεθος όλων των κορυφών σε bytes |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [CopyFrom](../../aspose.threed.entities/trimesh/copyfrom/)(TriMesh, VertexDeclaration) | Αντιγράψτε το `TriMesh` από την είσοδο με νέα διάταξη κορυφών |
| static [FromMesh](../../aspose.threed.entities/trimesh/frommesh/#frommesh)(Mesh, bool) | Δημιουργήστε ένα TriMesh από το δοσμένο αντικείμενο πλέγματος, η δήλωση κορυφών βασίζεται στη δομή του εισερχόμενου πλέγματος. |
| static [FromMesh](../../aspose.threed.entities/trimesh/frommesh/#frommesh_1)(VertexDeclaration, Mesh) | Δημιουργήστε ένα TriMesh από το δοσμένο αντικείμενο πλέγματος με τη δοσμένη διάταξη κορυφών. |
| static [FromRawData](../../aspose.threed.entities/trimesh/fromrawdata/)(VertexDeclaration, byte[], int[], bool) | Δημιουργήστε TriMesh από ακατέργαστα δεδομένα |
| [AddTriangle](../../aspose.threed.entities/trimesh/addtriangle/)(int, int, int) | Προσθέστε ένα νέο τρίγωνο |
| [BeginVertex](../../aspose.threed.entities/trimesh/beginvertex/)() | Ξεκινήστε την προσθήκη κορυφής |
| [EndVertex](../../aspose.threed.entities/trimesh/endvertex/)() | Ολοκληρώστε την προσθήκη κορυφής |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Λαμβάνει το πλαίσιο περιβάλλοντος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον renderer |
| [GetEnumerator](../../aspose.threed.entities/trimesh/getenumerator/)() | Αποκτήστε τον απαριθμητή για την απαρίθμηση του [`Vertex`](../../aspose.threed.utilities/vertex/) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [IndicesToArray](../../aspose.threed.entities/trimesh/indicestoarray/#indicestoarray)(out int[]) |  |
| [IndicesToArray](../../aspose.threed.entities/trimesh/indicestoarray/#indicestoarray_1)(out ushort[]) |  |
| [LoadVerticesFromBytes](../../aspose.threed.entities/trimesh/loadverticesfrombytes/)(byte[]) | Φορτώστε κορυφές από bytes, το μήκος των bytes πρέπει να είναι ακέραιο πολλαπλάσιο του μεγέθους της κορυφής. |
| [ReadDouble](../../aspose.threed.entities/trimesh/readdouble/)(int, VertexField) | Διαβάστε το πεδίο double |
| [ReadFloat](../../aspose.threed.entities/trimesh/readfloat/)(int, VertexField) | Διαβάστε το πεδίο float |
| [ReadFVector2](../../aspose.threed.entities/trimesh/readfvector2/)(int, VertexField) | Διαβάστε το πεδίο vector2 |
| [ReadFVector3](../../aspose.threed.entities/trimesh/readfvector3/)(int, VertexField) | Διαβάστε το πεδίο vector3 |
| [ReadFVector4](../../aspose.threed.entities/trimesh/readfvector4/)(int, VertexField) | Διαβάστε το πεδίο vector4 |
| [ReadVector2](../../aspose.threed.entities/trimesh/readvector2/)(int, VertexField) | Διαβάστε το πεδίο vector2 |
| [ReadVector3](../../aspose.threed.entities/trimesh/readvector3/)(int, VertexField) | Διαβάστε το πεδίο vector3 |
| [ReadVector4](../../aspose.threed.entities/trimesh/readvector4/)(int, VertexField) | Διαβάστε το πεδίο vector4 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |
| override [ToString](../../aspose.threed.entities/trimesh/tostring/)() | Λαμβάνει την αναπαράσταση συμβολοσειράς του `TriMesh` |
| [VerticesToArray](../../aspose.threed.entities/trimesh/verticestoarray/)() | Μετατρέψτε τα δεδομένα των κορυφών σε πίνακα byte |
| [Write16bIndicesTo](../../aspose.threed.entities/trimesh/write16bindicesto/)(Stream) | Γράψτε τα δεδομένα δεικτών ως 16-bit ακέραιο στη ροή |
| [Write32bIndicesTo](../../aspose.threed.entities/trimesh/write32bindicesto/)(Stream) | Γράψτε τα δεδομένα δεικτών ως 32-bit ακέραιο στο ρεύμα. |
| [WriteVerticesTo](../../aspose.threed.entities/trimesh/writeverticesto/)(Stream) | Γράψτε τα δεδομένα κορυφών στο καθορισμένο ρεύμα. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα TriMesh με προσαρμοσμένη διάταξη μνήμης και να το εξάγετε σε αρχείο.

```csharp
//Ορίστε μια δήλωση κορυφής ως {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//Μετατρέψτε ένα πλέγμα σε tri-mesh χρησιμοποιώντας την καθορισμένη διάταξη μνήμης
var mesh = (new Sphere()).ToMesh();
var triMesh = TriMesh.FromMesh(vd, mesh);
//Αποθηκεύστε το σε ρεύμα, 115 κορυφές * 32 bytes ανά κορυφή
using (var stream = new FileStream("output.bin", FileMode.Create))
{
    triMesh.WriteVerticesTo(stream);
    //Αποθηκεύστε τους δείκτες ως ushort σε ρεύμα, 504 δείκτες * 2 bytes ανά δείκτη
    triMesh.Write16bIndicesTo(stream);
}
```

### Δείτε επίσης

* class [Entity](../../aspose.threed/entity/)
* class [Vertex](../../aspose.threed.utilities/vertex/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


