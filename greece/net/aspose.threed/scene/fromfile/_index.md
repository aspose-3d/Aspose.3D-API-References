---
title: "Scene.FromFile"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Scene. Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου"
type: docs
weight: 20
url: /el/net/aspose.threed/scene/fromfile/
---
## FromFile(string, FileFormat, CancellationToken) {#fromfile_1}

Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

```csharp
public static Scene FromFile(string fileName, FileFormat format, 
    CancellationToken cancellationToken = default)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |
| μορφή | FileFormat | Μορφότυπος αρχείου. |
| cancellationToken | CancellationToken | Διακριτικό ακύρωσης για την εργασία φόρτωσης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ImportException](../../importexception/) | Εκτοπίζεται όταν η είσοδος δεν είναι έγκυρος 3D μορφότυπος. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε μια σκηνή από ένα αρχείο

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx", FileFormat.FBX7400ASCII, cts.Token);
```

### Δείτε επίσης

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string, LoadOptions, CancellationToken) {#fromfile_2}

Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

```csharp
public static Scene FromFile(string fileName, LoadOptions options, 
    CancellationToken cancellationToken = default)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |
| επιλογές | LoadOptions | Πιο λεπτομερής διαμόρφωση για το άνοιγμα του ρεύματος. |
| cancellationToken | CancellationToken | Διακριτικό ακύρωσης για την εργασία φόρτωσης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ImportException](../../importexception/) | Εκτοπίζεται όταν η είσοδος δεν είναι έγκυρος 3D μορφότυπος. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε μια σκηνή από ένα αρχείο

```csharp
var cts = new CancellationTokenSource();
var opt = new FbxLoadOptions();
opt.LookupPaths.Add("textures");
Scene scene = Scene.FromFile("input.fbx", opt, cts.Token);
```

### Δείτε επίσης

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string) {#fromfile}

Ανοίγει τη σκηνή από το δοσμένο μονοπάτι

```csharp
public static Scene FromFile(string fileName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ImportException](../../importexception/) | Εκτοπίζεται όταν η είσοδος δεν είναι έγκυρος 3D μορφότυπος. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε μια σκηνή από ένα αρχείο

```csharp
Scene scene = Scene.FromFile("input.fbx");
```

### Δείτε επίσης

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string, CancellationToken) {#fromfile_3}

Ανοίγει τη σκηνή από το δοσμένο μονοπάτι

```csharp
public static Scene FromFile(string fileName, CancellationToken cancellationToken)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |
| cancellationToken | CancellationToken | Διακριτικό ακύρωσης για την εργασία φόρτωσης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ImportException](../../importexception/) | Εκτοπίζεται όταν η είσοδος δεν είναι έγκυρος 3D μορφότυπος. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε μια σκηνή από ένα αρχείο

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx", cts.Token);
```

### Δείτε επίσης

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


