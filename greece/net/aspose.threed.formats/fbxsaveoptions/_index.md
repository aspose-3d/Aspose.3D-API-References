---
title: "Κλάση FbxSaveOptions"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Formats.FbxSaveOptions κλάση. Επιλογές αποθήκευσης για αρχείο Fbx"
type: docs
weight: 1180
url: /el/net/aspose.threed.formats/fbxsaveoptions/
---
## FbxSaveOptions class

Επιλογές αποθήκευσης για αρχείο Fbx.

```csharp
public class FbxSaveOptions : SaveOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [FbxSaveOptions](fbxsaveoptions/#constructor)(FileContentType) | Αρχικοποίηση ενός `FbxSaveOptions` χρησιμοποιώντας την πιο πρόσφατη υποστηριζόμενη έκδοση. |
| [FbxSaveOptions](fbxsaveoptions/#constructor_1)(FileFormat) | Αρχικοποιεί ένα `FbxSaveOptions` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [EmbedTextures](../../aspose.threed.formats/fbxsaveoptions/embedtextures/) { get; set; } | Λαμβάνει ή ορίζει εάν θα ενσωματωθεί η υφή στο τελικό αρχείο εξόδου. Ο FBX Exporter θα προσπαθήσει να βρει τα ακατέργαστα δεδομένα της υφής από [`FileSystem`](../ioconfig/filesystem/), και να ενσωματώσει το αρχείο στο τελικό αρχείο FBX. Η προεπιλεγμένη τιμή είναι ψευδής. |
| [EnableCompression](../../aspose.threed.formats/fbxsaveoptions/enablecompression/) { get; set; } | Συμπίεση μεγάλων δυαδικών δεδομένων στο αρχείο FBX (π.χ. δεδομένα κίνησης, σημεία ελέγχου, δεδομένα στοιχείων κορυφής, δείκτες), η προεπιλεγμένη τιμή είναι αληθής. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί. |
| [ExportLegacyMaterialProperties](../../aspose.threed.formats/fbxsaveoptions/exportlegacymaterialproperties/) { get; set; } | Λαμβάνει ή ορίζει αν εξάγονται οι παλαιές ιδιότητες υλικού, που χρησιμοποιούνται για συμβατότητα με παλαιότερες εκδόσεις. Αυτή η επιλογή είναι ενεργοποιημένη εξ ορισμού. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Προσπαθήστε να αντιγράψετε τις υφές που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [FoldRepeatedCurveData](../../aspose.threed.formats/fbxsaveoptions/foldrepeatedcurvedata/) { get; set; } | Λαμβάνει ή ορίζει αν επαναχρησιμοποιείται επαναλαμβανόμενα δεδομένα καμπύλης αυξάνοντας τον μετρητή αναφορών των τελευταίων δεδομένων. |
| [GenerateVertexElementMaterial](../../aspose.threed.formats/fbxsaveoptions/generatevertexelementmaterial/) { get; set; } | Λαμβάνει ή ορίζει αν πάντα δημιουργείται ένα [`VertexElementMaterial`](../../aspose.threed.entities/vertexelementmaterial/) για γεωμετρίες εάν ο συνημμένος κόμβος περιέχει υλικά. Αυτό είναι απενεργοποιημένο εξ ορισμού. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να ψάξει για το εξωτερικό αρχείο για φόρτωση. |
| [ReusePrimitiveMesh](../../aspose.threed.formats/fbxsaveoptions/reuseprimitivemesh/) { get; set; } | Επαναχρησιμοποίηση του πλέγματος για τα primitives με τις ίδιες παραμέτρους, αυτό θα μειώσει σημαντικά το μέγεθος του εξόδου FBX, όπου η σκηνή κατασκευάστηκε από μεγάλο σύνολο πρωτόγονων σχημάτων (όπως εισαγόμενα από αρχεία CAD). Η προεπιλεγμένη τιμή είναι ψευδής. |
| [VideoForTexture](../../aspose.threed.formats/fbxsaveoptions/videofortexture/) { get; set; } | Λαμβάνει ή ορίζει αν δημιουργείται ένα αντικείμενο Video για το [`Texture`](../../aspose.threed.shading/texture/) κατά την εξαγωγή ως FBX. |

### Δείτε επίσης

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


