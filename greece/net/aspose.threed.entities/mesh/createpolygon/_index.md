---
title: "Mesh.CreatePolygon"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Mesh. Δημιουργεί ένα νέο πολύγωνο με όλες τις κορυφές που ορίζονται σε δείκτες. Για δημιουργία πολύγωνου κορυφή προς κορυφή, παρακαλώ χρησιμοποιήστε το PolygonBuilder."
type: docs
weight: 60
url: /el/net/aspose.threed.entities/mesh/createpolygon/
---
## CreatePolygon(int[], int, int) {#createpolygon_3}

Δημιουργεί ένα νέο πολύγωνο με όλες τις κορυφές ορισμένες στα *indices*. Για να δημιουργήσετε το πολύγωνο κορυφή προς κορυφή, παρακαλούμε χρησιμοποιήστε [`PolygonBuilder`](../../polygonbuilder/).

```csharp
public void CreatePolygon(int[] indices, int offset, int length)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| indices | Int32[] | Πίνακας των δεικτών του πολυγώνου, κάθε δείκτης δείχνει σε ένα σημείο ελέγχου που σχηματίζει το πολύγωνο. |
| offset | Int32 | Η μετατόπιση του πρώτου δείκτη του πολυγώνου |
| length | Int32 | Το μήκος των δεικτών |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα νέο πολύγωνο με τους δείκτες των σημείων ελέγχου.

```csharp
var mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### Δείτε επίσης

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int[]) {#createpolygon_2}

Δημιουργεί ένα νέο πολύγωνο με όλες τις κορυφές ορισμένες στα *indices*. Για να δημιουργήσετε το πολύγωνο κορυφή προς κορυφή, παρακαλούμε χρησιμοποιήστε [`PolygonBuilder`](../../polygonbuilder/).

```csharp
public void CreatePolygon(int[] indices)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| indices | Int32[] | Πίνακας των δεικτών του πολυγώνου, κάθε δείκτης δείχνει σε ένα σημείο ελέγχου που σχηματίζει το πολύγωνο. |

## Παραδείγματα

```csharp
var mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### Δείτε επίσης

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int, int) {#createpolygon_1}

Δημιουργήστε ένα πολύγωνο με 4 κορυφές (τετράπλευρο)

```csharp
public void CreatePolygon(int v1, int v2, int v3, int v4)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| v1 | Int32 | Δείκτης της πρώτης κορυφής |
| v2 | Int32 | Δείκτης της δεύτερης κορυφής |
| v3 | Int32 | Δείκτης της τρίτης κορυφής |
| v4 | Int32 | Δείκτης της τέταρτης κορυφής |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα νέο πολύγωνο με τους δείκτες των σημείων ελέγχου.

```csharp
var mesh = new Mesh();
mesh.CreatePolygon(0, 1, 2, 3);
```

### Δείτε επίσης

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int) {#createpolygon}

Δημιουργήστε ένα πολύγωνο με 3 κορυφές (τρίγωνο)

```csharp
public void CreatePolygon(int v1, int v2, int v3)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| v1 | Int32 | Δείκτης της πρώτης κορυφής |
| v2 | Int32 | Δείκτης της δεύτερης κορυφής |
| v3 | Int32 | Δείκτης της τρίτης κορυφής |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα νέο πολύγωνο με τους δείκτες των σημείων ελέγχου.

```csharp
var mesh = new Mesh();
mesh.CreatePolygon(0, 1, 2);
```

### Δείτε επίσης

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


