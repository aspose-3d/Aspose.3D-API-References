---
title: CreatePolygon
second_title: Aspose.3D untuk .NET API Referensi
description: Membuat poligon baru dengan semua simpul yang ditentukanindices . Untuk membuat simpul poligon demi simpul silakan gunakanPolygonBuilderaspose.threed.entities/polygonbuilder/ .
type: docs
weight: 50
url: /id/net/aspose.threed.entities/mesh/createpolygon/
---
## CreatePolygon(int[], int, int) {#createpolygon_3}

Membuat poligon baru dengan semua simpul yang ditentukan*indices* . Untuk membuat simpul poligon demi simpul, silakan gunakan[`PolygonBuilder`](../../polygonbuilder/) .

```csharp
public void CreatePolygon(int[] indices, int offset, int length)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| indices | Int32[] | Susunan indeks poligon, setiap indeks menunjuk ke titik kontrol yang membentuk poligon. |
| offset | Int32 | Offset indeks poligon pertama |
| length | Int32 | Panjang indeks |

### Contoh

```csharp
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### Lihat juga

* class [Mesh](../)
* ruang nama [Aspose.ThreeD.Entities](../../mesh/)
* perakitan [Aspose.3D](../../../)

---

## CreatePolygon(int[]) {#createpolygon_2}

Membuat poligon baru dengan semua simpul yang ditentukan*indices* . Untuk membuat simpul poligon demi simpul, silakan gunakan[`PolygonBuilder`](../../polygonbuilder/) .

```csharp
public void CreatePolygon(int[] indices)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| indices | Int32[] | Susunan indeks poligon, setiap indeks menunjuk ke titik kontrol yang membentuk poligon. |

### Contoh

```csharp
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### Lihat juga

* class [Mesh](../)
* ruang nama [Aspose.ThreeD.Entities](../../mesh/)
* perakitan [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int, int) {#createpolygon_1}

Buat poligon dengan 4 simpul (segi empat)

```csharp
public void CreatePolygon(int v1, int v2, int v3, int v4)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| v1 | Int32 | Indeks simpul pertama |
| v2 | Int32 | Indeks simpul kedua |
| v3 | Int32 | Indeks simpul ketiga |
| v4 | Int32 | Indeks simpul keempat |

### Lihat juga

* class [Mesh](../)
* ruang nama [Aspose.ThreeD.Entities](../../mesh/)
* perakitan [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int) {#createpolygon}

Buat poligon dengan 3 simpul (segitiga)

```csharp
public void CreatePolygon(int v1, int v2, int v3)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| v1 | Int32 | Indeks simpul pertama |
| v2 | Int32 | Indeks simpul kedua |
| v3 | Int32 | Indeks simpul ketiga |

### Lihat juga

* class [Mesh](../)
* ruang nama [Aspose.ThreeD.Entities](../../mesh/)
* perakitan [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
