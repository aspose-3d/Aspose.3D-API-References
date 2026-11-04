---
title: "Mesh.Optimize"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Metode Mesh. Optimalkan penggunaan memori mesh dengan menghilangkan titik kontrol yang duplikat"
type: docs
weight: 100
url: /id/net/aspose.threed.entities/mesh/optimize/
---
## Optimize(bool) {#optimize}

Optimalkan penggunaan memori mesh dengan menghilangkan titik kontrol yang duplikat

```csharp
public Mesh Optimize(bool vertexElements)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vertexElements | Boolean | Optimalkan data elemen vertex yang duplikat |

### Nilai Kembalian

Instansi mesh baru dengan penggunaan memori yang kompak

## Contoh

Kode berikut menunjukkan cara menghilangkan titik kontrol yang duplikat dari mesh yang belum dioptimalkan:

```csharp
//Sphere.ToMesh menghasilkan 117 titik kontrol
var mesh = (new Sphere()).ToMesh();
//Setelah dioptimalkan, hanya tersisa 86 titik kontrol, indeks poligon juga dipetakan ulang.
var optimized = mesh.Optimize(true);
```

### Lihat Juga

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Optimize(bool, float, float, float) {#optimize_1}

Optimalkan penggunaan memori mesh dengan menghilangkan titik kontrol yang duplikat

```csharp
public Mesh Optimize(bool vertexElements, float toleranceControlPoint = 1E-09, 
    float toleranceNormal = 1E-09, float toleranceUV = 1E-09)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vertexElements | Boolean | Optimalkan data elemen vertex yang duplikat |
| toleranceControlPoint | Tunggal | Toleransi untuk titik kontrol, nilai default adalah 1e-9 |
| toleranceNormal | Tunggal | Toleransi untuk normal/tangen/binormal, nilai default adalah 1e-9 |
| toleranceUV | Tunggal | Toleransi untuk uv, nilai default adalah 1e-9 |

### Nilai Kembalian

Instansi mesh baru dengan penggunaan memori yang kompak

### Lihat Juga

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


