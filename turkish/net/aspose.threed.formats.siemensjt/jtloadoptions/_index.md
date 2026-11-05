---
title: "Sınıf JtLoadOptions"
second_title: "Aspose.3D for .NET API Referansı"
description: "Aspose.ThreeD.Formats.SiemensJT.JtLoadOptions sınıf. Siemens JT için yükleme seçenekleri"
type: docs
weight: 1380
url: /tr/net/aspose.threed.formats.siemensjt/jtloadoptions/
---
## JtLoadOptions class

Siemens JT için yükleme seçenekleri

```csharp
public class JtLoadOptions : LoadOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [JtLoadOptions](jtloadoptions/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Metin tabanlı dosyalar için varsayılan kodlamayı alır veya ayarlar. Varsayılan değer null'dur, bu da içe aktarıcı/dışa aktarıcının hangi kodlamayı kullanacağını belirleyeceği anlamına gelir.(Inherited from [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Mevcut Kaydet/Yükle seçeneğinde belirtilen dosya biçimini alır.(Inherited from [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Dışa aktarma/içeri aktarma sahnesinin dosya adı. Bu isteğe bağlıdır, ancak OBJ'nin materyali gibi dış varlıkları serileştirirken faydalıdır.(Inherited from [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Kullanıcının yükleme/kaydetme sırasında dış bağımlılıkları nasıl yöneteceğini ele almasına izin verir.(Inherited from [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [LoadPMI](../../aspose.threed.formats.siemensjt/jtloadoptions/loadpmi/) { get; set; } | Mümkünse JT dosyasından PMI bilgilerini yükle, veri [`AssetInfo`](../../aspose.threed/scene/assetinfo/) özelliği "PMI" olarak kaydedilecektir. Varsayılan değer yanlıştır. |
| [LoadProperties](../../aspose.threed.formats.siemensjt/jtloadoptions/loadproperties/) { get; set; } | JT'nin özellik tablosundan Aspose.3D özellikleri olarak özellikleri yükle. Varsayılan değer yanlıştır. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | OBJ gibi bazı dosyalar dış dosyalara bağımlıdır, arama yolları Aspose.3D'nin dış dosyayı yüklemek için bulmasını sağlar.(Inherited from [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |

### Ayrıca Bakınız

* class [LoadOptions](../../aspose.threed.formats/loadoptions/)
* namespace [Aspose.ThreeD.Formats.SiemensJT](../../aspose.threed.formats.siemensjt/)
* assembly [Aspose.3D](../../)


