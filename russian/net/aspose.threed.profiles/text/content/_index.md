---
title: "Text.Content"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство Text. Содержимое текста"
type: docs
weight: 20
url: /ru/net/aspose.threed.profiles/text/content/
---
## Text.Content property

Содержание текста

```csharp
public string Content { get; set; }
```

## Примеры

Следующий код показывает, как создать 3D‑сетку из текста, используя указанный файл шрифта.

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

### См. также

* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


