---
title: "FontFile.FromFile"
second_title: "Aspose.3D for .NET API Referansı"
description: "FontFile yöntemi. FontFile'ı dosya adından yükle"
type: docs
weight: 10
url: /tr/net/aspose.threed.profiles/fontfile/fromfile/
---
## FontFile.FromFile method

FontFile'ı dosya adından yükle

```csharp
public static FontFile FromFile(string fileName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | String | Yazı tipi dosyasının yolu |

### Dönüş Değeri

FontFile örneği

### İstisnalar

| istisna | koşul |
| --- | --- |
| IOException | Dosyadan okuma başarısız olduğunda atılır. |

## Örnekler

Aşağıdaki kod, belirtilen yazı tipi dosyasını kullanarak metinden 3B örgü nasıl oluşturulacağını gösterir.

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### Ayrıca Bakınız

* class [FontFile](../)
* namespace [Aspose.ThreeD.Profiles](../../fontfile/)
* assembly [Aspose.3D](../../../)


