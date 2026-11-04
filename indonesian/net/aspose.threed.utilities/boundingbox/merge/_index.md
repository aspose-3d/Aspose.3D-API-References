---
title: "BoundingBox.Merge"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Metode BoundingBox. Menggabungkan kotak pembatas saat ini dengan titik yang diberikan"
type: docs
weight: 130
url: /id/net/aspose.threed.utilities/boundingbox/merge/
---
## Merge(Vector4) {#merge_2}

Gabungkan kotak pembatas saat ini dengan titik yang diberikan

```csharp
public void Merge(Vector4 pt)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pt | Vector4 | Titik yang akan digabungkan ke dalam kotak pembatas |

## Contoh

Kode berikut menunjukkan cara menggabungkan titik ke kotak pembatas.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector4(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### Lihat Juga

* struct [Vector4](../../vector4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(Vector3) {#merge_1}

Gabungkan kotak pembatas saat ini dengan titik yang diberikan

```csharp
public void Merge(Vector3 pt)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pt | Vector3 | Titik yang akan digabungkan ke dalam kotak pembatas |

## Contoh

Kode berikut menunjukkan cara menggabungkan titik ke kotak pembatas.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector3(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### Lihat Juga

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(double, double, double) {#merge_3}

Gabungkan kotak pembatas saat ini dengan titik yang diberikan

```csharp
public void Merge(double x, double y, double z)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | Double | Titik yang akan digabungkan ke dalam kotak pembatas |
| y | Double | Titik yang akan digabungkan ke dalam kotak pembatas |
| z | Double | Titik yang akan digabungkan ke dalam kotak pembatas |

## Contoh

Kode berikut menunjukkan cara menggabungkan titik ke kotak pembatas.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(1, 10, -1);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Lihat Juga

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(BoundingBox) {#merge}

Menggabungkan kotak baru ke dalam kotak pembatas saat ini.

```csharp
public void Merge(BoundingBox bb)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bb | BoundingBox | Kotak pembatas untuk digabungkan |

### Lihat Juga

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


