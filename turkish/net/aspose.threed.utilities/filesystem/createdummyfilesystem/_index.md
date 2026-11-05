---
title: "FileSystem.CreateDummyFileSystem"
second_title: "Aspose.3D for .NET API Referansı"
description: "FileSystem yöntemi. Sahte bir dosya sistemi oluşturun, okuma/yazma işlemleri sahte işlemlerdir"
type: docs
weight: 10
url: /tr/net/aspose.threed.utilities/filesystem/createdummyfilesystem/
---
## FileSystem.CreateDummyFileSystem method

Sahte bir dosya sistemi oluşturun, okuma/yazma işlemleri sahte işlemlerdir.

```csharp
public static FileSystem CreateDummyFileSystem()
```

### Dönüş Değeri

Sahte bir dosya sistemi

## Örnekler

Aşağıdaki kod, dosyanın belleğe nasıl dışa aktarılacağını ve tüm bağımlı dosya oluşturmanın nasıl yok sayılacağını gösterir.

```csharp
//Malzeme ile bir sahne oluşturun
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//Bir kaydetme seçeneği oluşturun ve dosya sistemini belirtin, böylece bağımlı dosya belleğe yazılacaktır
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = FileSystem.CreateDummyFileSystem();
opt.FileSystem = dfs;
//obj'nin malzeme dosya adı, obj'nin dosya adıyla ilişkilidir, bu yüzden açık bir isim gerekir.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### Ayrıca Bakınız

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


