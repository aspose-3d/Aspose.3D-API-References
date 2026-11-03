---
title: "DracoFormat.Encode"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος DracoFormat. Κωδικοποίηση της οντότητας σε καθορισμένο stream"
type: docs
weight: 20
url: /el/net/aspose.threed.formats/dracoformat/encode/
---
## Encode(Entity, Stream, DracoSaveOptions) {#encode_1}

Κωδικοποίηση της οντότητας σε καθορισμένη ροή

```csharp
public void Encode(Entity entity, Stream stream, DracoSaveOptions options = null)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| οντότητα | Οντότητα | Η οντότητα που θα κωδικοποιηθεί |
| stream | Stream | Το stream στο οποίο θα γραφτούν τα κωδικοποιημένα δεδομένα |
| επιλογές | DracoSaveOptions | Επιπλέον επιλογές για την κωδικοποίηση του νέφους σημείων |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοξεύεται όταν αποτύχει η ανάγνωση από το stream |

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string, DracoSaveOptions) {#encode_2}

Κωδικοποίηση της οντότητας σε καθορισμένο αρχείο

```csharp
public void Encode(Entity entity, string fileName, DracoSaveOptions options = null)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| οντότητα | Οντότητα | Η οντότητα που θα κωδικοποιηθεί |
| fileName | String | Το όνομα αρχείου που θα γραφτεί |
| επιλογές | DracoSaveOptions | Επιπλέον επιλογές για την κωδικοποίηση του νέφους σημείων |

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, DracoSaveOptions) {#encode}

Κωδικοποίηση της οντότητας σε ακατέργαστα δεδομένα Draco

```csharp
public byte[] Encode(Entity entity, DracoSaveOptions options = null)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| οντότητα | Οντότητα | Η οντότητα που θα κωδικοποιηθεί |
| επιλογές | DracoSaveOptions | Επιπλέον επιλογές για την κωδικοποίηση του νέφους σημείων |

### Τιμή επιστροφής

Τα κωδικοποιημένα δεδομένα draco που αντιπροσωπεύονται σε bytes

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)


