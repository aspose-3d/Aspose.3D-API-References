---
title: "Text.FontSize"
second_title: "Aspose.3D for .NET API Referansı"
description: "Text özelliği. Yazı tipi boyutu ölçeği"
type: docs
weight: 40
url: /tr/net/aspose.threed.profiles/text/fontsize/
---
## Text.FontSize property

Yazı tipi boyutu ölçeği.

```csharp
public float FontSize { get; set; }
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


