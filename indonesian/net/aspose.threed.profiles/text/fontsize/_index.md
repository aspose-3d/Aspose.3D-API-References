---
title: "Text.FontSize"
second_title: "Referensi API Aspose.3D untuk .NET"
description: "Properti Text. Skala ukuran font"
type: docs
weight: 40
url: /id/net/aspose.threed.profiles/text/fontsize/
---
## Text.FontSize property

Skala ukuran font.

```csharp
public float FontSize { get; set; }
```

## Contoh

Kode berikut menunjukkan cara membuat mesh 3D dari teks menggunakan file font yang ditentukan.

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

### Lihat Juga

* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


