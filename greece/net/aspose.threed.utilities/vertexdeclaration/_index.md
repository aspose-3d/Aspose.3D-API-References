---
title: "Κλάση VertexDeclaration"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Utilities.VertexDeclaration κλάση. Η δήλωση μιας προσαρμοσμένης δομής κορυφών"
type: docs
weight: 2910
url: /el/net/aspose.threed.utilities/vertexdeclaration/
---
## VertexDeclaration class

Η δήλωση μιας προσαρμοσμένης δομής κορυφής

```csharp
public sealed class VertexDeclaration : IComparable<VertexDeclaration>, IEnumerable<VertexField>
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [VertexDeclaration](vertexdeclaration/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Count](../../aspose.threed.utilities/vertexdeclaration/count/) { get; } | Λαμβάνει τον αριθμό όλων των πεδίων που ορίζονται σε αυτό το `VertexDeclaration` |
| [Item](../../aspose.threed.utilities/vertexdeclaration/item/) { get; } |  |
| [Sealed](../../aspose.threed.utilities/vertexdeclaration/sealed/) { get; } | Ένα `VertexDeclaration` θα σφραγιστεί όταν έχει χρησιμοποιηθεί από [`TriMesh`](../../aspose.threed.entities/trimesh-1/) ή [`TriMesh`](../../aspose.threed.entities/trimesh/), δεν επιτρέπονται περαιτέρω τροποποιήσεις. |
| [Size](../../aspose.threed.utilities/vertexdeclaration/size/) { get; } | Το μέγεθος σε byte της δομής κορυφής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/vertexdeclaration/fromgeometry/)(Geometry, bool) | Δημιουργήστε ένα `VertexDeclaration` βασισμένο στη διάταξη ενός [`Geometry`](../../aspose.threed.entities/geometry/). |
| static [FromType&lt;T&gt;](../../aspose.threed.utilities/vertexdeclaration/fromtype/)() |  |
| [AddField](../../aspose.threed.utilities/vertexdeclaration/addfield/)(VertexFieldDataType, VertexFieldSemantic, int, string) | Προσθέστε ένα νέο πεδίο κορυφής |
| [Clear](../../aspose.threed.utilities/vertexdeclaration/clear/)() | Καθαρίστε όλα τα πεδία. |
| [CompareTo](../../aspose.threed.utilities/vertexdeclaration/compareto/)(VertexDeclaration) | Συγκρίνει αυτήν την παρουσίαση με ένα καθορισμένο αντικείμενο και επιστρέφει ένδειξη των σχετικών τιμών τους. |
| override [Equals](../../aspose.threed.utilities/vertexdeclaration/equals/)(object) | Καθορίζει εάν αυτή η παρουσία και ένα συγκεκριμένο αντικείμενο, το οποίο πρέπει επίσης να είναι αντικείμενο `VertexDeclaration`, έχουν την ίδια τιμή. |
| [GetEnumerator](../../aspose.threed.utilities/vertexdeclaration/getenumerator/)() | Λαμβάνει έναν enumerator για να διασχίσει όλα τα πεδία κορυφής σε αυτήν την παρουσία. |
| override [GetHashCode](../../aspose.threed.utilities/vertexdeclaration/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτή τη συμβολοσειρά. |
| override [ToString](../../aspose.threed.utilities/vertexdeclaration/tostring/)() | Αναπαράσταση συμβολοσειράς του `VertexDeclaration` |

### Δείτε επίσης

* class [VertexField](../vertexfield/)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


