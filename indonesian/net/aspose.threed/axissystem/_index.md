---
title: "Kelas AxisSystem"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Kelas Aspose.ThreeD.AxisSystem. Sistem sumbu adalah kombinasi vektor atas dan vektor depan dari sistem koordinat"
type: docs
weight: 150
url: /id/net/aspose.threed/axissystem/
---
## AxisSystem class

Sistem sumbu adalah kombinasi sistem koordinat, vektor atas, dan vektor depan.

```csharp
public class AxisSystem
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [AxisSystem](axissystem/#constructor)(Axis, Axis?) |  |
| [AxisSystem](axissystem/#constructor_1)(CoordinateSystem, Axis) | Membuat sistem sumbu baru |
| [AxisSystem](axissystem/#constructor_2)(CoordinateSystem, Axis, Axis) | Membuat sistem sumbu baru |
| [AxisSystem](axissystem/#constructor_3)(CoordinateSystem?, Axis?, Axis?) |  |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CoordinateSystem](../../aspose.threed/axissystem/coordinatesystem/) { get; } | Mendapatkan sistem koordinat dari sistem sumbu ini. |
| [Front](../../aspose.threed/axissystem/front/) { get; } | Mendapatkan vektor depan dari sistem sumbu ini |
| [Up](../../aspose.threed/axissystem/up/) { get; } | Mendapatkan vektor atas dari sistem sumbu ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromAssetInfo](../../aspose.threed/axissystem/fromassetinfo/)(AssetInfo) | Buat `AxisSystem` dari [`AssetInfo`](../assetinfo/) |
| [TransformTo](../../aspose.threed/axissystem/transformto/)(AxisSystem) | Buat matriks yang digunakan untuk mengonversi dari sistem sumbu saat ini ke sistem sumbu target. |

### Lihat Juga

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


