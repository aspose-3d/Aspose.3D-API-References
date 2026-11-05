---
title: "Text.Font"
second_title: "Aspose.3D for .NET API Referansı"
description: "Text özelliği. Metnin yazı tipi"
type: docs
weight: 30
url: /tr/net/aspose.threed.profiles/text/font/
---
## Text.Font property

Metnin yazı tipi.

```csharp
public FontFile Font { get; set; }
```

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

* class [FontFile](../../fontfile/)
* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


