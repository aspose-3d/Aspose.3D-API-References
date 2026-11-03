---
title: "License.SetLicense"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος License. Παρέχει άδεια στο στοιχείο"
type: docs
weight: 20
url: /el/net/aspose.threed/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Αδειοδοτεί το στοιχείο.

```csharp
public void SetLicense(string licenseName)
```

## Παρατηρήσεις

Προσπαθεί να βρει την άδεια στις ακόλουθες τοποθεσίες:

1. Ρητή διαδρομή.

2. Ο φάκελος που περιέχει το assembly του στοιχείου Aspose.

3. Ο φάκελος που περιέχει το assembly που καλεί ο πελάτης.

4. Ο φάκελος που περιέχει το entry (startup) assembly.

5. Ένας ενσωματωμένος πόρος στο assembly που καλεί ο πελάτης.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Ρητή διαδρομή.

2. Ένας ενσωματωμένος πόρος στο assembly που καλεί ο πελάτης.

2. Ο φάκελος που περιέχει το αρχείο JAR του στοιχείου Aspose.

3. Ο φάκελος που περιέχει το αρχείο JAR που καλεί ο πελάτης.

## Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να βρεθεί ένα αρχείο άδειας με όνομα MyLicense.lic στον φάκελο που περιέχει το στοιχείο, στον φάκελο που περιέχει το καλούμενο assembly, στον φάκελο του entry assembly και, τέλος, στους ενσωματωμένους πόρους του καλούμενου assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

το αρχείο jar του στοιχείου:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου ή όνομα ενσωματωμένου πόρου. Χρησιμοποιήστε μια κενή συμβολοσειρά για να μεταβείτε σε λειτουργία αξιολόγησης.

### Δείτε επίσης

* class [License](../)
* namespace [Aspose.ThreeD](../../license/)
* assembly [Aspose.3D](../../../)

---

## SetLicense(Stream) {#setlicense}

Αδειοδοτεί το στοιχείο.

```csharp
public void SetLicense(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Μία ροή που περιέχει την άδεια. |

## Παρατηρήσεις

Χρησιμοποιήστε αυτή τη μέθοδο για να φορτώσετε μια άδεια από ροή.

## Παραδείγματα

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)

License license = new License();
license.setLicense(myStream);
```

### Δείτε επίσης

* class [License](../)
* namespace [Aspose.ThreeD](../../license/)
* assembly [Aspose.3D](../../../)


