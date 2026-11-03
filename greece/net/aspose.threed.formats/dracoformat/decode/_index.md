---
title: "DracoFormat.Decode"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος DracoFormat. Αποκωδικοποίηση του νέφους σημείων ή του πλέγματος από το καθορισμένο όνομα αρχείου"
type: docs
weight: 10
url: /el/net/aspose.threed.formats/dracoformat/decode/
---
## Decode(string) {#decode_1}

Αποκωδικοποίηση του νέφους σημείων ή του πλέγματος από το καθορισμένο όνομα αρχείου

```csharp
public Geometry Decode(string fileName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Το όνομα αρχείου περιέχει το αρχείο drc |

### Τιμή επιστροφής

Μια παρουσία [`Mesh`](../../../aspose.threed.entities/mesh/) ή [`PointCloud`](../../../aspose.threed.entities/pointcloud/) εξαρτάται από το περιεχόμενο του αρχείου

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοξεύεται όταν αποτυγχάνει η ανάγνωση από το αρχείο |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να κωδικοποιήσετε και να αποκωδικοποιήσετε ένα Mesh σε/από πίνακα byte:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//κωδικοποίηση πλέγματος σε μορφή Draco
byte[] draco = FileFormat.Draco.Encode(mesh);
//αποκωδικοποίηση πλέγματος από μορφή Draco
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### Δείτε επίσης

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(byte[]) {#decode}

Αποκωδικοποίηση του νέφους σημείων ή του πλέγματος από δεδομένα μνήμης

```csharp
public Geometry Decode(byte[] data)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δεδομένα | Byte[] | Τα ακατέργαστα bytes drc |

### Τιμή επιστροφής

Μια παρουσία [`Mesh`](../../../aspose.threed.entities/mesh/) ή [`PointCloud`](../../../aspose.threed.entities/pointcloud/) εξαρτάται από το περιεχόμενο

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [ImportException](../../../aspose.threed/importexception/) | Εκτοξεύεται όταν τα δεδομένα είναι κακοδιαμορφωμένα. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να κωδικοποιήσετε και να αποκωδικοποιήσετε ένα Mesh σε/από πίνακα byte:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//κωδικοποίηση πλέγματος σε μορφή Draco
byte[] draco = FileFormat.Draco.Encode(mesh);
//αποκωδικοποίηση πλέγματος από μορφή Draco
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### Δείτε επίσης

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)


