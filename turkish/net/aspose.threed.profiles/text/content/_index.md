---
title: "Text.Content"
second_title: "Aspose.3D for .NET API Referansı"
description: "Text özelliği. Metnin içeriği"
type: docs
weight: 20
url: /tr/net/aspose.threed.profiles/text/content/
---
## Text.Content property

Metnin içeriği

```csharp
public string Content { get; set; }
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

* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


