---
title: PlySaveOptions
second_title: Aspose.3D for .NET API Referansı
description: Sahneyi PLY dosyası olarak dışa aktarma seçeneklerini kaydedin.
type: docs
weight: 1300
url: /tr/net/aspose.threed.formats/plysaveoptions/
---
## PlySaveOptions class

Sahneyi PLY dosyası olarak dışa aktarma seçeneklerini kaydedin.

```csharp
public class PlySaveOptions : SaveOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PlySaveOptions](plysaveoptions#constructor)() | Oluşturucusu[`PlySaveOptions`](../plysaveoptions) |
| [PlySaveOptions](plysaveoptions#constructor_1)(FileContentType) | Oluşturucusu[`PlySaveOptions`](../plysaveoptions) |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ColorComponents](../../aspose.threed.formats/plysaveoptions/colorcomponents) { get; set; } | Köşe rengi için bileşen adları, varsayılan değer ("kırmızı", "yeşil", "mavi") |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding) { get; set; } | Metin tabanlı dosyalar için varsayılan kodlamayı alır veya ayarlar. Varsayılan değer null'dur; bu, içe aktaran/dışa aktaran kişinin hangi kodlamanın kullanılacağına karar vereceği anlamına gelir. |
| [FaceElement](../../aspose.threed.formats/plysaveoptions/faceelement) { get; set; } | Yüz verileri için öğe adı, varsayılan değer "yüz"dür |
| [FaceProperty](../../aspose.threed.formats/plysaveoptions/faceproperty) { get; set; } | Yüz verileri için özellik adı, varsayılan değer "vertex_index" |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat) { get; } | Geçerli Kaydet/Yükle seçeneğinde belirtilen dosya biçimini alır. |
| [FileName](../../aspose.threed.formats/ioconfig/filename) { get; set; } | Dışa aktarma/içe aktarma sahnesinin dosya adı. Bu isteğe bağlıdır, ancak OBJ'nin malzemesi gibi harici varlıkları seri hale getirirken kullanışlıdır. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem) { get; set; } | Kullanıcının, yükleme/kaydetme sırasında harici bağımlılıkları nasıl yöneteceğini yönetmesine izin verin. |
| [FlipCoordinate](../../aspose.threed.formats/plysaveoptions/flipcoordinate) { get; set; } | Sahneyi kaydederken koordinatı çevirin, varsayılan değer true |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths) { get; set; } | OBJ gibi bazı dosyalar harici dosyaya bağlıdır, arama yolları Aspose.3D'nin yüklenecek harici dosyayı aramasını sağlar. |
| [NormalComponents](../../aspose.threed.formats/plysaveoptions/normalcomponents) { get; set; } | Normal veriler için bileşen adları, varsayılan değer ("nx", "ny", "nz") |
| [PointCloud](../../aspose.threed.formats/plysaveoptions/pointcloud) { get; set; } | Sahneyi nokta bulutu olarak dışa aktarın, varsayılan değer false'tur. |
| [PositionComponents](../../aspose.threed.formats/plysaveoptions/positioncomponents) { get; set; } | Konum verileri için bileşen adları, varsayılan değer ("x", "y", "z") |
| [TextureCoordinateComponents](../../aspose.threed.formats/plysaveoptions/texturecoordinatecomponents) { get; set; } | Doku koordinat verileri için bileşen adları, varsayılan değer ("u", "v") |
| [VertexElement](../../aspose.threed.formats/plysaveoptions/vertexelement) { get; set; } | Köşe verileri için öğe adı, varsayılan değer "köşe"dir |

### Ayrıca bakınız

* class [SaveOptions](../saveoptions)
* ad alanı [Aspose.ThreeD.Formats](../../aspose.threed.formats)
* toplantı [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->