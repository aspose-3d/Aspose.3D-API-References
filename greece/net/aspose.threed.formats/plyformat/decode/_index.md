---
title: "PlyFormat.Decode"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "PlyFormat method. Αποκωδικοποίηση ενός νέφους σημείων ή πλέγματος από το καθορισμένο ρεύμα"
type: docs
weight: 10
url: /el/net/aspose.threed.formats/plyformat/decode/
---
## Decode(string) {#decode_2}

Αποκωδικοποίηση ενός νέφους σημείων ή πλέγματος από τη συγκεκριμένη ροή.

```csharp
public Geometry Decode(string fileName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Το ρεύμα εισόδου |

### Τιμή επιστροφής

Μια παρουσία [`Mesh`](../../../aspose.threed.entities/mesh/) ή [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αποκωδικοποιήσετε ένα πλέγμα από αρχείο PLY:

```csharp
//Δημιουργήστε ένα αρχείο δοκιμής για αποκωδικοποίηση
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Αποκωδικοποιήστε το αρχείο
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Δείτε επίσης

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(string, PlyLoadOptions) {#decode_3}

Αποκωδικοποίηση ενός νέφους σημείων ή πλέγματος από τη συγκεκριμένη ροή.

```csharp
public Geometry Decode(string fileName, PlyLoadOptions opt)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Το ρεύμα εισόδου |
| opt | PlyLoadOptions | Η επιλογή φόρτωσης της μορφής PLY |

### Τιμή επιστροφής

Μια παρουσία [`Mesh`](../../../aspose.threed.entities/mesh/) ή [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αποκωδικοποιήσετε ένα πλέγμα από αρχείο PLY:

```csharp
//Δημιουργήστε ένα αρχείο δοκιμής για αποκωδικοποίηση
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Αποκωδικοποιήστε το αρχείο
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Δείτε επίσης

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyLoadOptions](../../plyloadoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(Stream) {#decode}

Αποκωδικοποίηση ενός νέφους σημείων ή πλέγματος από τη συγκεκριμένη ροή.

```csharp
public Geometry Decode(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Το ρεύμα εισόδου |

### Τιμή επιστροφής

Μια παρουσία [`Mesh`](../../../aspose.threed.entities/mesh/) ή [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αποκωδικοποιήσετε ένα πλέγμα από αρχείο PLY:

```csharp
//Δημιουργήστε ένα αρχείο δοκιμής για αποκωδικοποίηση
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Αποκωδικοποιήστε το αρχείο
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Δείτε επίσης

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(Stream, PlyLoadOptions) {#decode_1}

Αποκωδικοποίηση ενός νέφους σημείων ή πλέγματος από τη συγκεκριμένη ροή.

```csharp
public Geometry Decode(Stream stream, PlyLoadOptions opt)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Το ρεύμα εισόδου |
| opt | PlyLoadOptions | Η επιλογή φόρτωσης της μορφής PLY |

### Τιμή επιστροφής

Μια παρουσία [`Mesh`](../../../aspose.threed.entities/mesh/) ή [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αποκωδικοποιήσετε ένα πλέγμα από αρχείο PLY:

```csharp
//Δημιουργήστε ένα αρχείο δοκιμής για αποκωδικοποίηση
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Αποκωδικοποιήστε το αρχείο
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Δείτε επίσης

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyLoadOptions](../../plyloadoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)


