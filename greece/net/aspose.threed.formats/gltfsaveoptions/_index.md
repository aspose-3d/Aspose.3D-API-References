---
title: "Κλάση GltfSaveOptions"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Formats.GltfSaveOptions. Επιλογές αποθήκευσης για τη μορφή glTF"
type: docs
weight: 1280
url: /el/net/aspose.threed.formats/gltfsaveoptions/
---
## GltfSaveOptions class

Επιλογές αποθήκευσης για μορφή glTF.

```csharp
public class GltfSaveOptions : SaveOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [GltfSaveOptions](gltfsaveoptions/#constructor)(FileContentType) | Κατασκευαστής του `GltfSaveOptions` |
| [GltfSaveOptions](gltfsaveoptions/#constructor_1)(FileFormat) | Κατασκευαστής του `GltfSaveOptions` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ApplyUnitScale](../../aspose.threed.formats/gltfsaveoptions/applyunitscale/) { get; set; } | Εφαρμόστε το [`UnitScaleFactor`](../../aspose.threed/assetinfo/unitscalefactor/) στο πλέγμα. Η προεπιλεγμένη τιμή είναι false. |
| [BufferFile](../../aspose.threed.formats/gltfsaveoptions/bufferfile/) { get; set; } | Το όνομα αρχείου του εξωτερικού αρχείου buffer που χρησιμοποιείται για την αποθήκευση δυαδικών δεδομένων. Εάν αυτό το αρχείο δεν καθοριστεί, το Aspose.3D θα δημιουργήσει ένα όνομα για εσάς. Αυτό αγνοείται όταν εξάγετε glTF σε δυαδική λειτουργία. |
| [DracoCompression](../../aspose.threed.formats/gltfsaveoptions/dracocompression/) { get; set; } | Λαμβάνει ή ορίζει αν ενεργοποιηθεί η συμπίεση draco |
| [EmbedAssets](../../aspose.threed.formats/gltfsaveoptions/embedassets/) { get; set; } | Ενσωματώνει όλα τα εξωτερικά στοιχεία ως base64 σε ένα μόνο αρχείο σε λειτουργία ASCII, η προεπιλεγμένη τιμή είναι false. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Προσπαθήστε να αντιγράψετε τις υφές που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [ExternalDracoEncoder](../../aspose.threed.formats/gltfsaveoptions/externaldracoencoder/) { get; set; } | Χρησιμοποιήστε εξωτερικό κωδικοποιητή draco για να επιταχύνετε την ταχύτητα συμπίεσης draco. |
| [FallbackNormal](../../aspose.threed.formats/gltfsaveoptions/fallbacknormal/) { get; set; } | Όταν ο εξαγωγέας GLTF2 εντοπίσει ένα μη έγκυρο κανονικό διάνυσμα, αυτό θα χρησιμοποιηθεί αντί της αρχικής τιμής του για να παρακάμψει την επικύρωση. Η προεπιλεγμένη τιμή είναι (0, 1, 0). |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [FlipTexCoordV](../../aspose.threed.formats/gltfsaveoptions/fliptexcoordv/) { get; set; } | Αναστρέψτε το συντεταγμένο υφής v(t), η προεπιλεγμένη τιμή είναι true. |
| [ImageFormat](../../aspose.threed.formats/gltfsaveoptions/imageformat/) { get; set; } | Το τυπικό glTF υποστηρίζει μόνο PNG/JPG ως μορφή υφής, αυτή η επιλογή θα καθοδηγήσει πώς το Aspose.3D θα μετατρέπει τις μη τυπικές εικόνες σε υποστηριζόμενη μορφή κατά την εξαγωγή. Η προεπιλεγμένη τιμή είναι Png. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να ψάξει για το εξωτερικό αρχείο για φόρτωση. |
| [MaterialConverter](../../aspose.threed.formats/gltfsaveoptions/materialconverter/) { get; set; } | Προσαρμοσμένος μετατροπέας για τη μετατροπή του υλικού της γεωμετρίας σε υλικό PBR. Εάν δεν έχει οριστεί, ο εξαγωγέας glTF 2.0 θα μετατρέπει αυτόματα το τυπικό υλικό σε υλικό PBR. Η προεπιλεγμένη τιμή είναι null. Αυτή η ιδιότητα χρησιμοποιείται κατά την εξαγωγή μιας σκηνής σε αρχείο glTF 2.0. |
| [PrettyPrint](../../aspose.threed.formats/gltfsaveoptions/prettyprint/) { get; set; } | Το περιεχόμενο JSON του αρχείου GLTF είναι εσοχή για ανθρώπινη ανάγνωση, η προεπιλεγμένη τιμή είναι false. |
| [SaveExtras](../../aspose.threed.formats/gltfsaveoptions/saveextras/) { get; set; } | Αποθηκεύει τις δυναμικές ιδιότητες του αντικειμένου σκηνής σε πεδία 'extra' στο παραγόμενο αρχείο glTF. Αυτό είναι χρήσιμο για την παροχή δεδομένων ειδικών για την εφαρμογή. Η προεπιλεγμένη τιμή είναι false. |
| [UseCommonMaterials](../../aspose.threed.formats/gltfsaveoptions/usecommonmaterials/) { get; set; } | Σειριοποιεί τα υλικά χρησιμοποιώντας τις κοινές επεκτάσεις υλικού KHR, η προεπιλεγμένη τιμή είναι false. Ορίζοντας αυτό σε false θα κάνει το Aspose.3D να εξάγει ένα σύνολο σκίασης κορυφής/κατακερματισμού εάν ExportShaders. |

### Δείτε επίσης

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


