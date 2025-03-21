---
title: Text.FontSize
second_title: Aspose.3D for .NET API Reference
description: Text property. Font size scale
type: docs
weight: 40
url: /net/aspose.threed.profiles/text/fontsize/
---
## Text.FontSize property

Font size scale.

```csharp
public float FontSize { get; set; }
```

## Examples

The following code shows how to create a 3D mesh from text using specified font file.

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

### See Also

* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


