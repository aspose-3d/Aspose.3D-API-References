---
title: "Κλάση Discreet3dsSaveOptions"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Formats.Discreet3dsSaveOptions κλάση. Επιλογές αποθήκευσης για αρχείο 3DS"
type: docs
weight: 1130
url: /el/net/aspose.threed.formats/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

Επιλογές αποθήκευσης για αρχείο 3DS.

```csharp
public class Discreet3dsSaveOptions : SaveOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Discreet3dsSaveOptions](discreet3dssaveoptions/)() | Κατασκευαστής του `Discreet3dsSaveOptions` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [DuplicatedNameCounterBase](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterbase/) { get; set; } | Ο μετρητής που χρησιμοποιείται για τη δημιουργία νέου ονόματος για διπλότυπα ονόματα, η προεπιλεγμένη τιμή είναι 2. |
| [DuplicatedNameCounterFormat](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterformat/) { get; set; } | Η μορφή του διπλότυπου μετρητή, η προεπιλεγμένη τιμή είναι κενή συμβολοσειρά. |
| [DuplicatedNameSeparator](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednameseparator/) { get; set; } | Ο διαχωριστής μεταξύ του ονόματος του αντικειμένου και του διπλότυπου μετρητή, η προεπιλεγμένη τιμή είναι "_". Όταν η σκηνή περιέχει αντικείμενα που χρησιμοποιούν το ίδιο όνομα, ο εξαγωγέας 3DS του Aspose.3D θα δημιουργήσει διαφορετικό όνομα για το αντικείμενο. Για παράδειγμα, υπάρχουν δύο κόμβοι με όνομα "Box", ο πρώτος κόμβος θα έχει το όνομα "Box", και ο δεύτερος κόμβος θα λάβει νέο όνομα "Box_2" χρησιμοποιώντας την προεπιλεγμένη διαμόρφωση. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί. |
| [ExportCamera](../../aspose.threed.formats/discreet3dssaveoptions/exportcamera/) { get; set; } | Λαμβάνει ή ορίζει αν θα εξαχθούν όλες οι κάμερες στη σκηνή. |
| [ExportLight](../../aspose.threed.formats/discreet3dssaveoptions/exportlight/) { get; set; } | Λαμβάνει ή ορίζει αν θα εξαχθούν όλα τα φώτα στη σκηνή. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Προσπαθήστε να αντιγράψετε τις υφές που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [FlipCoordinateSystem](../../aspose.threed.formats/discreet3dssaveoptions/flipcoordinatesystem/) { get; set; } | Λαμβάνει ή ορίζει την αντιστροφή του συστήματος συντεταγμένων των σημείων ελέγχου/κανονικών κατά την εισαγωγή/εξαγωγή. |
| [GammaCorrectedColor](../../aspose.threed.formats/discreet3dssaveoptions/gammacorrectedcolor/) { get; set; } | Ένα αρχείο 3ds μπορεί να περιέχει το αρχικό χρώμα και το χρώμα διορθωμένο με γάμμα για το ίδιο χαρακτηριστικό. Ορίζοντας αυτό σε true θα χρησιμοποιηθεί το χρώμα διορθωμένο με γάμμα αν είναι δυνατόν, διαφορετικά το Aspose.3D θα προσπαθήσει να χρησιμοποιήσει το αρχικό χρώμα. |
| [HighPreciseColor](../../aspose.threed.formats/discreet3dssaveoptions/highprecisecolor/) { get; set; } | Αν αυτό είναι true, το παραγόμενο αρχείο 3ds θα χρησιμοποιεί χρώμα υψηλής ακρίβειας, δηλαδή κάθε κανάλι κόκκινο/πράσινο/μπλε είναι σε 32-bit float. Διαφορετικά, το παραγόμενο αρχείο θα χρησιμοποιεί χρώμα 24-bit, κάθε κανάλι χρησιμοποιεί 8-bit byte. Η προεπιλεγμένη τιμή είναι false, επειδή δεν υποστηρίζουν όλες οι εφαρμογές το χρώμα υψηλής ακρίβειας. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να ψάξει για το εξωτερικό αρχείο για φόρτωση. |
| [MasterScale](../../aspose.threed.formats/discreet3dssaveoptions/masterscale/) { get; set; } | Λαμβάνει ή ορίζει την κύρια κλίμακα που χρησιμοποιείται κατά την εξαγωγή. |

### Δείτε επίσης

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


