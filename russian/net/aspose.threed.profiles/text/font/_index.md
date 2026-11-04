---
title: "Text.Font"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство Text. Шрифт текста"
type: docs
weight: 30
url: /ru/net/aspose.threed.profiles/text/font/
---
## Text.Font property

Шрифт текста.

```csharp
public FontFile Font { get; set; }
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

* class [FontFile](../../fontfile/)
* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


