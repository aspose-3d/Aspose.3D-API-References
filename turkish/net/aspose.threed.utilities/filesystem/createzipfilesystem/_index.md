---
title: "FileSystem.CreateZipFileSystem"
second_title: "Aspose.3D for .NET API Referansı"
description: "FileSystem yöntemi. Belirtilen zip dosyasına veya zip akışına yalnızca okuma erişimi sağlamak için bir dosya sistemi oluşturun. Dosya sistemi, açma/kaydetme işleminden sonra yok edilecektir."
type: docs
weight: 40
url: /tr/net/aspose.threed.utilities/filesystem/createzipfilesystem/
---
## CreateZipFileSystem(Stream, string) {#createzipfilesystem}

Belirtilen zip dosyasına veya zip akışına yalnızca okuma erişimi sağlamak için bir dosya sistemi oluşturun. Dosya sistemi, açma/kaydetme işleminden sonra yok edilecektir.

```csharp
public static FileSystem CreateZipFileSystem(Stream stream, string baseDir = "/")
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | Stream | Zip dosyasına erişmek için akış |
| baseDir | String | Zip dosyasının içindeki temel dizin. |

### Dönüş Değeri

Bir zip dosya sistemi

### İstisnalar

| istisna | koşul |
| --- | --- |
| IOException | Akıştan okuma başarısız olduğunda atılır. |

## Açıklamalar

Bu, yalnızca okunabilir bir dosya sistemidir, bu yüzden yazma işlemleri desteklenmez.

## Örnekler

Aşağıdaki kod, dosyanın nasıl içe aktarılacağını ve bir zip arşiv dosyasında bağımlı dosyaların nasıl sağlanacağını gösterir.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//Bir yükleme seçenekleri örneği oluşturun ve bir zip dosya sistemi belirtin
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//dosyayı yükle
var scene = Scene.FromFile(inputFile, opt);
```

### Ayrıca Bakınız

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)

---

## CreateZipFileSystem(string) {#createzipfilesystem_1}

Belirtilen zip dosyasına veya zip akışına yalnızca okunabilir erişim sağlamak için dosya sistemi. Dosya sistemi, açma/kaydetme işleminden sonra yok edilecektir.

```csharp
public static FileSystem CreateZipFileSystem(string fileName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | String | Zip dosyasının dosya adı. |

### Dönüş Değeri

Bir zip dosya sistemi

### İstisnalar

| istisna | koşul |
| --- | --- |
| IOException | Akıştan okuma başarısız olduğunda atılır. |

## Örnekler

Aşağıdaki kod, dosyanın nasıl içe aktarılacağını ve bir zip arşiv dosyasında bağımlı dosyaların nasıl sağlanacağını gösterir.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//Bir yükleme seçenekleri örneği oluşturun ve bir zip dosya sistemi belirtin
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//dosyayı yükle
var scene = Scene.FromFile(inputFile, opt);
```

### Ayrıca Bakınız

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


