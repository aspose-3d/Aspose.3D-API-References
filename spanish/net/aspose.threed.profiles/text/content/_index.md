---
title: "Text.Content"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Text propiedad. Contenido del texto"
type: docs
weight: 20
url: /es/net/aspose.threed.profiles/text/content/
---
## Text.Content property

Contenido del texto

```csharp
public string Content { get; set; }
```

## Ejemplos

El siguiente código muestra cómo crear una malla 3D a partir del texto usando el archivo de fuente especificado.

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

### Ver también

* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


