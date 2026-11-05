---
title: "FileSystem.CreateLocalFileSystem"
second_title: "Aspose.3D for .NET API Referansı"
description: "FileSystem yöntemi. Yalnızca yerel dizine erişen yeni bir FileSystem başlatın. Bu FileSystem örneğindeki tüm dosya okuma/yazma belirtilen dizine eşlenecektir."
type: docs
weight: 20
url: /tr/net/aspose.threed.utilities/filesystem/createlocalfilesystem/
---
## FileSystem.CreateLocalFileSystem method

Yeni bir [`FileSystem`](../) başlatın; yalnızca yerel dizine erişir. Bu FileSystem örneğindeki tüm dosya okuma/yazma belirtilen dizine eşlenecektir.

```csharp
public static FileSystem CreateLocalFileSystem(string directory)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dizin | String | Fiziksel dosya sisteminizdeki dizin, sanal kök dizin olarak kullanılır. |

### Dönüş Değeri

Yerel dosya erişimi sağlamak için yeni bir dosya sistemi örneği

### İstisnalar

| istisna | koşul |
| --- | --- |
| FileNotFoundException | Dizin bulunamadığında fırlatılır. |

## Örnekler

Aşağıdaki kod, dosyanın nasıl içe aktarılacağını ve verilen bir dizinde bağımlı dosyaların nasıl sağlanacağını gösterir.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//bir yükleme seçenekleri örneği oluşturun ve yerel bir dosya sistemi belirtin
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateLocalFileSystem("textures/");
//dosyayı yükle
var scene = Scene.FromFile(inputFile, opt);
```

### Ayrıca Bakınız

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


