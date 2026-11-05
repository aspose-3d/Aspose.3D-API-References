---
title: "Sınıf JtLoadOptions"
second_title: "Aspose.3D for .NET API Referansı"
description: "Aspose.ThreeD.Formats.JtLoadOptions sınıfı. Siemens JT için yükleme seçenekleri"
type: docs
weight: 1310
url: /tr/net/aspose.threed.formats/jtloadoptions/
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
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Metin tabanlı dosyalar için varsayılan kodlamayı alır veya ayarlar. Varsayılan değer null'dır, bu da içe aktarıcı/aktarının hangi kodlamayı kullanacağına karar vereceği anlamına gelir. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Mevcut Kaydet/Yükle seçeneğinde belirtilen dosya formatını alır. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Dışa aktarma/içe aktarma sahnesinin dosya adı. Bu isteğe bağlıdır, ancak OBJ'nin malzemesi gibi harici varlıkları serileştirirken faydalıdır. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Kullanıcının yükleme/kaydetme sırasında harici bağımlılıkları nasıl yöneteceğini ele almasına izin ver. |
| [LoadPMI](../../aspose.threed.formats/jtloadoptions/loadpmi/) { get; set; } | Mümkünse JT dosyasından PMI bilgilerini yükle, veri [`AssetInfo`](../../aspose.threed/scene/assetinfo/) özelliği "PMI" olarak kaydedilecektir. Varsayılan değer yanlıştır. |
| [LoadProperties](../../aspose.threed.formats/jtloadoptions/loadproperties/) { get; set; } | JT'nin özellik tablosundan Aspose.3D özellikleri olarak özellikleri yükle. Varsayılan değer yanlıştır. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | OBJ gibi bazı dosyalar harici dosyalara bağımlıdır, arama yolları Aspose.3D'nin yüklemek için harici dosyayı bulmasını sağlar. |

### Ayrıca Bakınız

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


