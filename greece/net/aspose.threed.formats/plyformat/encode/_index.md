---
title: "PlyFormat.Encode"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "PlyFormat method. Κωδικοποίηση της οντότητας και αποθήκευση του αποτελέσματος στο ρεύμα"
type: docs
weight: 20
url: /el/net/aspose.threed.formats/plyformat/encode/
---
## Encode(Entity, Stream) {#encode}

Κωδικοποίηση της οντότητας και αποθήκευση του αποτελέσματος στη ροή.

```csharp
public void Encode(Entity entity, Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| οντότητα | Οντότητα | Η οντότητα για κωδικοποίηση |
| stream | Stream | Το ρεύμα για εγγραφή, αυτή η μέθοδος δεν θα κλείσει αυτό το ρεύμα |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να κωδικοποιήσετε ένα πλέγμα σε αρχείο PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//κωδικοποιήστε το πλέγμα σε μορφή PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### Δείτε επίσης

* class [Entity](../../../aspose.threed/entity/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, Stream, PlySaveOptions) {#encode_1}

Κωδικοποίηση της οντότητας και αποθήκευση του αποτελέσματος στη ροή.

```csharp
public void Encode(Entity entity, Stream stream, PlySaveOptions opt)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| οντότητα | Οντότητα | Η οντότητα για κωδικοποίηση |
| stream | Stream | Το ρεύμα για εγγραφή, αυτή η μέθοδος δεν θα κλείσει αυτό το ρεύμα |
| opt | PlySaveOptions | Επιλογές αποθήκευσης |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να κωδικοποιήσετε ένα πλέγμα σε αρχείο PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//κωδικοποιήστε το πλέγμα σε μορφή PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### Δείτε επίσης

* class [Entity](../../../aspose.threed/entity/)
* class [PlySaveOptions](../../plysaveoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string) {#encode_2}

Κωδικοποίηση της οντότητας και αποθήκευση του αποτελέσματος σε εξωτερικό αρχείο.

```csharp
public void Encode(Entity entity, string fileName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| οντότητα | Οντότητα | Η οντότητα για κωδικοποίηση |
| fileName | String | Το αρχείο για εγγραφή |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να κωδικοποιήσετε ένα πλέγμα σε αρχείο PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//κωδικοποιήστε το πλέγμα σε μορφή PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### Δείτε επίσης

* class [Entity](../../../aspose.threed/entity/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string, PlySaveOptions) {#encode_3}

Κωδικοποίηση της οντότητας και αποθήκευση του αποτελέσματος σε εξωτερικό αρχείο.

```csharp
public void Encode(Entity entity, string fileName, PlySaveOptions opt)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| οντότητα | Οντότητα | Η οντότητα για κωδικοποίηση |
| fileName | String | Το αρχείο για εγγραφή |
| opt | PlySaveOptions | Επιλογές αποθήκευσης |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να κωδικοποιήσετε ένα πλέγμα σε αρχείο PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//κωδικοποιήστε το πλέγμα σε μορφή PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### Δείτε επίσης

* class [Entity](../../../aspose.threed/entity/)
* class [PlySaveOptions](../../plysaveoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)


